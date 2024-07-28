<script lang="ts">
    import Button from "$lib/components/ui/button/button.svelte";
    import ResumeCard from "$lib/components/ResumeCard.svelte";
    import Title from "$lib/components/Title.svelte"
    import Container from "$lib/components/Container.svelte"

</script>

<Container>
  <Title title="Resume"/>
    <div class="pt-16 flex flex-col gap-8">
        <div class="flex justify-between items-center">
            <span class="text-2xl font-bold"> Education </span>
            <Button>Download CV</Button>
        </div>
        <ResumeCard
            date="2023-Present"
            title="Computer Science Bachelor"
            company="Umm
        Al-Qura University"
        >
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Delectus enim modi, ea saepe nihil fugit sapiente maiores ullam
                maxime deleniti aspernatur laboriosam nemo porro voluptatibus
                alias dolor, aliquid ipsam accusamus!
            </p>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Delectus enim modi, ea saepe nihil fugit sapiente maiores ullam
                maxime deleniti aspernatur laboriosam nemo porro voluptatibus
                alias dolor, aliquid ipsam accusamus!
            </p>
        </ResumeCard>

        <ResumeCard
            date="2023-Present"
            title="Computer Science Bachelor"
            company="Umm Al-Qura University"
        >
            Hello World!
        </ResumeCard>
    </div>
</Container>      