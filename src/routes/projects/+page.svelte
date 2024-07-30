<script lang="ts">
    import Container from "$lib/components/Container.svelte";
    import ProjectsCard from "$lib/components/ProjectsCard.svelte";
    import Title from "$lib/components/Title.svelte";
    import { Button } from "$lib/components/ui/button";
</script>

<Container class="flex flex-col gap-16">
    <Title title="Projects" />

    <!-- <p>
        "This calculator is simple and easy to use. It has a clear display and
        buttons that are arranged neatly for doing basic math like adding and
        subtracting. If you make a mistake, there's a button to start over
        easily. It's designed to make math quick and simple for everyone,
        helping you get your calculations done without any hassle.
    </p> -->

    <ProjectsCard
        title="Anas"
        subtitle="Simple Calculator"
        imgSrc="/Calculator.jpeg"
    >
        <ul class="list-disc">
            <li>Clean layout with a blue display bar at the top</li>
            <li>Grid pattern arrangement of circular buttons</li>
            <li>Simple and minimalistic design</li>
            <li>Clear button for resetting the display</li>
            <li>User-friendly interface for basic arithmetic calculations</li>
            <li>Handling incorrect calcuation made by the user</li>
        </ul>
        <a href="https://itsanas121.github.io/calculator/" target="_blank"
            ><Button>Try it!</Button></a
        >
    </ProjectsCard>

    <ProjectsCard title="Anas" subtitle="A To-Do List" imgSrc="/todolist.jpeg ">
        <ul class="list-disc">
            <li>Easy to use</li>
            <li>Set reminders and due times for tasks</li>
            <li>View all tasks or filter by daily tasks</li>
            <li>Mark tasks as completed</li>
            <li>Add new tasks</li>
            <li>Delete or edit tasks</li>
            <li>Move tasks to a completed tasks list</li>
            <li>Sort tasks by priority</li>
            <li>Progressive Web App Support</li>
        </ul>
        <a href="https://todolist-anas.netlify.app/" target="_blank"
            ><Button>Try it!</Button></a
        >
    </ProjectsCard>
</Container>
