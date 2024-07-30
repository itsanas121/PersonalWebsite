<script>
   import SocialMedia from "$lib/components/SocialMedia.svelte";
   import Button from "$lib/components/ui/button/button.svelte";
</script>
<svelte:head>
   <title>
      Anas
   </title>
</svelte:head>
<div class="flex justify-end pb-[35rem] lg:pb-0">
   <div
      class="bg-secondary text-secondary-foreground relative w-full lg:w-[60vw] min-h-[40vh] lg:min-h-[calc(100vh-10.5rem)] flex justify-center items-center pb-32"
   >
      <div
         class="bg-[#f4ece6] dark:bg-[#1E3853] shadow-[0_10px_60px_-15px_rgba(0,0,0,0.8)] w-[22rem] absolute lg:start-10 lg:-translate-x-full flex flex-col items-center justify-between pt-8 gap-4 self-bottom lg:self-start translate-y-[105%] lg:translate-y-[10%] max-w-[85vw]"
      >
         <img
            src="/programmer.jpg"
            class="rounded-full w-64 mx-auto grayscale"
            alt="الصورة الشخصية"
         />

         <div class="flex flex-col items-center gap-8">
            <h1 class="font-bold text-4xl dark:text-[#2196F3]">Anas</h1>
            <hr class="w-28 border-2 border-primary" />
            <h2 class="text-2xl dark:text-[#2196F3]">Web Developer</h2>
         </div>
         <div
            class="bg-secondary text-secondary-foreground w-full flex justify-center p-2 mt-12"
         >
            <SocialMedia />
            <!-- <Button
               variant="ghost"
               size="icon"
               href="https://x.com/itsanas121"
               target="_blank"
            >
               <svg
                  class="h-auto w-6"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  ><path
                     fill="currentColor"
                     d="M18.205 2.25h3.308l-7.227 8.26l8.502 11.24H16.13l-5.214-6.817L4.95 21.75H1.64l7.73-8.835L1.215 2.25H8.04l4.713 6.231zm-1.161 17.52h1.833L7.045 4.126H5.078z"
                  /></svg
               >
            </Button>
            <Button
               variant="ghost"
               size="icon"
               href="https://www.linkedin.com/in/anas-almehmadi-29b206276"
               target="_blank"
            >
               <svg
                  class="h-auto w-6"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  ><path
                     fill="currentColor"
                     d="M18.336 18.339h-2.665v-4.177c0-.996-.02-2.278-1.39-2.278c-1.389 0-1.601 1.084-1.601 2.205v4.25h-2.666V9.75h2.56v1.17h.035c.358-.674 1.228-1.387 2.528-1.387c2.7 0 3.2 1.778 3.2 4.092v4.714M7.004 8.575a1.546 1.546 0 0 1-1.548-1.549a1.548 1.548 0 1 1 1.547 1.549m1.336 9.764H5.667V9.75H8.34zM19.67 3H4.33C3.594 3 3 3.58 3 4.297v15.406C3 20.42 3.594 21 4.328 21h15.339C20.4 21 21 20.42 21 19.703V4.297C21 3.581 20.4 3 19.666 3z"
                  /></svg
               >
            </Button>
            <Button
               variant="ghost"
               size="icon"
               href="https://www.instagram.com/itsanas242/"
               target="_blank"
            >
               <svg
                  class="h-auto w-6"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  ><path
                     fill="currentColor"
                     d="M12.001 9a3 3 0 1 0 0 6a3 3 0 0 0 0-6m0-2a5 5 0 1 1 0 10a5 5 0 0 1 0-10m6.5-.25a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1 2.5 0M12.001 4c-2.474 0-2.878.007-4.029.058c-.784.037-1.31.142-1.798.332a2.9 2.9 0 0 0-1.08.703a2.9 2.9 0 0 0-.704 1.08c-.19.49-.295 1.015-.331 1.798C4.007 9.075 4 9.461 4 12c0 2.475.007 2.878.058 4.029c.037.783.142 1.31.331 1.797c.17.435.37.748.702 1.08c.337.336.65.537 1.08.703c.494.191 1.02.297 1.8.333C9.075 19.994 9.461 20 12 20c2.475 0 2.878-.007 4.029-.058c.782-.037 1.308-.142 1.797-.331a2.9 2.9 0 0 0 1.08-.703c.337-.336.538-.649.704-1.08c.19-.492.296-1.018.332-1.8c.052-1.103.058-1.49.058-4.028c0-2.474-.007-2.878-.058-4.029c-.037-.782-.143-1.31-.332-1.798a2.9 2.9 0 0 0-.703-1.08a2.9 2.9 0 0 0-1.08-.704c-.49-.19-1.016-.295-1.798-.331C14.926 4.006 14.54 4 12 4m0-2c2.717 0 3.056.01 4.123.06c1.064.05 1.79.217 2.427.465c.66.254 1.216.598 1.772 1.153a4.9 4.9 0 0 1 1.153 1.772c.247.637.415 1.363.465 2.428c.047 1.066.06 1.405.06 4.122s-.01 3.056-.06 4.122s-.218 1.79-.465 2.428a4.9 4.9 0 0 1-1.153 1.772a4.9 4.9 0 0 1-1.772 1.153c-.637.247-1.363.415-2.427.465c-1.067.047-1.406.06-4.123.06s-3.056-.01-4.123-.06c-1.064-.05-1.789-.218-2.427-.465a4.9 4.9 0 0 1-1.772-1.153a4.9 4.9 0 0 1-1.153-1.772c-.248-.637-.415-1.363-.465-2.428C2.012 15.056 2 14.717 2 12s.01-3.056.06-4.122s.217-1.79.465-2.428a4.9 4.9 0 0 1 1.153-1.772A4.9 4.9 0 0 1 5.45 2.525c.637-.248 1.362-.415 2.427-.465C8.945 2.013 9.284 2 12.001 2"
                  /></svg
               >
            </Button> -->
         </div>
      </div>
      <div class="mx-10 max-w-[30rem] flex flex-col gap-8">
         <h1 class="text-8xl font-bold">Hello</h1>
         <h4 class="text-4xl">Here's who I am and what I do</h4>
         <div class="flex gap-2">
            <Button href="/resume" variant="outline" class="w-32">Resume</Button
            >
            <Button href="/projects" variant="outline" class="w-32"
               >Projects</Button
            >
         </div>
         <div class="flex flex-col gap-2">
            <p>
               A Sophomore Computer Science student at Umm Al-Qura University,
               intersted in Data Science, Web Development, and exploring the
               endless possibilities at the intersection of technology and
               innovation
            </p>
         </div>
      </div>
   </div>
</div>
