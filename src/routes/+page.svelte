<script>
    import couplePic from '$lib/assets/images/couple-pic.jpg?enhanced';
    import couplePic2 from '$lib/assets/images/couple-pic-2.jpg?enhanced';
</script>

<main class="container">
    <section class="page1">
        <div class="text-section">
            <div class="flex justify-between">
                <span>Your presence is requested</span>
            </div>
            <div>
                <span>To celebrate</span>
            </div>
            <div>
                <span>The wedding of</span>
            </div>
            <div class="flex justify-center py-5">
                <span class="font-greatvibes! text-[2.5em]! text-accent font-normal! tracking-wider">Indri & Adhis</span>
            </div>
            <div class="flex justify-center">
                <span>29.11.25</span>
            </div>
        </div>

        <div class="image-section">
            <div class="image-wrapper">
                <enhanced:img fetchpriority="high" src={couplePic} alt="couplePic1"/>
            </div>
        </div>
    </section>

    <section class="page2">
        <div class="text-section">
            <div class="text-justify py-10">
                <span>"And among His signs is that He created for you from yourselves mates that you may find tranquility in them; and He placed between you affection and mercy. Indeed in that are signs for a people who give thought."</span>
            </div>
            <div class="">
                <span class="italic">QS. Ar-Rum: 21</span>
            </div>
        </div>

        <div class="image-section relative">
            <div class="small-image-wrapper">
                <enhanced:img fetchpriority="high" class="small-image" src={couplePic2} alt="couplePic2"/>
            </div>
            <div class="big-image-wrapper">
                <enhanced:img fetchpriority="high" class="" src={couplePic2} alt="couplePic2"/>
            </div>
        </div>
    </section>
</main>