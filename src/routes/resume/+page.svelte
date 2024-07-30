<script lang="ts">
    import Button from "$lib/components/ui/button/button.svelte";
    import ResumeCard from "$lib/components/ResumeCard.svelte";
    import Title from "$lib/components/Title.svelte";
    import Container from "$lib/components/Container.svelte";
</script>
<svelte:head>
   <title>
  Resume
   </title>
</svelte:head>
<Container>
    <Title title="Resume" />
    <div class="pt-16 flex flex-col gap-8">
        <div class="flex justify-between items-center">
            <span class="text-2xl font-bold"> Experience </span>
            <!-- <Button><href="CV.pdf" download="MY CV"></Button> -->
             <a href="CV.pdf" download="CV">
               <Button>Download CV</Button>
                        </div>
        <ResumeCard
            date="01/2024 - present"
            title="Head of Organizational committee "
            company="UQU Computing Club"
        >
        <p class="font-bold text-red-400">
            <a href="https://x.com/uqucc" class="clickable" target="_blank"
                >UQUCC's site</a
            >
        </p>
            <ul class="list-disc">
                <li>Crowd organization</li>
                <li>Assigning tasks to team members</li>
                <li>Problem solving</li>
                <li>Planning and coordinating events</li>
                <li>Evaluation and feedback</li>
            </ul>
        </ResumeCard>

        <ResumeCard
            date="01/2024 - 08/2024"
            title="Co-leader of Activites Management committee"
            company="Google Developer Students Club"
        >
        <p class="font-bold text-red-400">
            <a href="https://x.com/gdscuqu" class="clickable" target="_blank"
                >GDSCUQU's site</a
            >
        </p>
            <ul class="list-disc">
                <li>Planning and organizing activities</li>
                <li>Assigning tasks to team members</li>
                <li>Task delegation</li>
                <li>Team collaboration</li>
                <li>Event execution</li>
                <li>Evaluation and feedback</li>
            </ul>
        </ResumeCard>
        <ResumeCard
            date="06/2024 - present"
            title="Co-leader of Human Resource Management"
            company="Keptar Community"
        >
            <p class="font-bold text-red-400">
                <a href="https://x.com/keptar_sa" class="clickable" target="_blank"
                    >KEPTAR's site</a
                >
            </p>
            <ul class="list-disc">
                <li>Recruitment and Onboarding</li>
                <li>Training and Development</li>
                <li>Conflict Resolution</li>
                <li>Performance Management:</li>
                <li>Community Engagement</li>
                <li>Assigning Volunteer Hours to Members</li>
                <li>Email Communication Management for Members</li>
            </ul>
        </ResumeCard>
    </div>
</Container>
