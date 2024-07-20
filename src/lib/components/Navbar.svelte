<script>
    import Button from "./ui/button/button.svelte";
    import { page } from "$app/stores";
    import * as Sheet from "$lib/components/ui/sheet";

    const links = [
        {
            text: "About me",
            href: "/",
        },
        {
            text: "Resume",
            href: "/resume",
        },
        {
            text: "Projects",
            href: "/projects",
        },
        {
            text: "Contact",
            href: "/contact",
        },
    ];
    let isSheetOpen = false;
</script>

<div class=" w-[100dvw] bg-secondary text-secondary-foreground py-8 px-6">
    <nav class="max-w-screen-2xl flex justify-between items-center mx-auto">
        <div class="flex items-center gap-2">
            <div class="bg-primary w-5 h-5 me-4" />
            <div class="flex items-end gap-2">
                <span class="font-bold text-3xl"> Anas </span>
                <span class="text-xl uppercase"> / Web Developer </span>
            </div>
        </div>
        <div>
            <div class="uppercase hidden md:flex">
                {#each links as link}
                    <Button
                        class=" {$page.url.pathname == link.href &&
                            'text-primary'}"
                        href={link.href}
                        variant="link">{link.text}</Button
                    >
                {/each}
            </div>

            <Sheet.Root bind:open={isSheetOpen}>
                <Sheet.Trigger  class="flex md:hidden" >
                    <Button variant="ghost" size="icon">
                        <svg
                            class="w-12 h-auto"
                            xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 24 24"
                            ><circle
                                cx="4"
                                cy="12"
                                r="1"
                                fill="currentColor"
                            /><rect
                                width="14"
                                height="2"
                                x="7"
                                y="11"
                                fill="currentColor"
                                rx=".94"
                                ry=".94"
                            /><rect
                                width="18"
                                height="2"
                                x="3"
                                y="16"
                                fill="currentColor"
                                rx=".94"
                                ry=".94"
                            /><rect
                                width="18"
                                height="2"
                                x="3"
                                y="6"
                                fill="currentColor"
                                rx=".94"
                                ry=".94"
                            /></svg
                        >
                    </Button>
                </Sheet.Trigger>
                <Sheet.Content class="flex flex-col justify-center">
                    {#each links as link}
                        <Button
                            class=" text-xl {$page.url.pathname == link.href &&
                                'text-primary'}"
                            href={link.href}
                            variant="link"
                            on:click={() => (isSheetOpen = false)}
                            >{link.text}</Button
                        >
                    {/each}
                </Sheet.Content>
            </Sheet.Root>
        </div>
    </nav>
</div>
