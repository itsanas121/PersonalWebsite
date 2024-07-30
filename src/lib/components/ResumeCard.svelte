<script lang="ts">
    export let date: string;
    export let title: string;
    export let company: string;
</script>

<div class="bg-secondary text-secondary-foreground p-8 shadow-xl flex flex-col sm:flex-row  items-center gap-16">
    <div class="flex flex-col min-w-[11rem]">
        <span>
            {company}
        </span>
        <span class="text-primary font-semibold"> {date}</span>
        <span class="font-bold"> {title}</span>
    </div>

    <div class="w-full">
        <slot />
    </div>
</div>
