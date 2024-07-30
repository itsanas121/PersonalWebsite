<script lang="ts">
    import Container from "$lib/components/Container.svelte";
    import Title from "$lib/components/Title.svelte";
    import { Button } from "$lib/components/ui/button";
    import { Input } from "$lib/components/ui/input/index.js";
    import { Label } from "$lib/components/ui/label/index.js";
    import Textarea from "$lib/components/ui/textarea/textarea.svelte";
</script>

<Container class="flex flex-col gap-16">
    <Title title="Let's Talk!" />
    <form
        action="https://formsubmit.co/anascs2023@gmail.com"
        method="POST"
        class="bg-secondary text-secondary-foreground p-8 flex flex-col gap-8"
    >
        <div>
            <Label for="name">Full Name</Label>
            <Input
                required
                name="name"
                id="name"
                placeholder="Enter your name"
            />
        </div>
        <div>
            <Label for="email">Email</Label>
            <Input
                required
                type="email"
                name="email"
                id="email"
                placeholder="name@example.com"
            />
        </div>
        <div>
            <Label for="subject">Subject</Label>
            <Input required name="subject" id="subject" placeholder="...." />
        </div>
        <div>
            <Label for="message">Message</Label>
            <Textarea required name="message" id="message" placeholder="...." />
        </div>
        <Button type="submit" class="max-w-32">Send</Button>
    </form>
</Container>
