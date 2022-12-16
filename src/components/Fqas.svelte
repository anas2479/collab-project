
<div class="max-w-6xl mx-auto p-4">
    <h2 class="text-5xl text-gray-700 font-heading mb-4">Frequently Asked Questions</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        {#each questions as question}
            <div class="bg-white shadow-md rounded-lg p-4">
                <h3 class="text-xl font-bold mb-2">{question.question}</h3>
                <p>{question.answer}</p>
            </div>
        {/each}
    </div>
</div>


<script>
    import questions from "../questions";
</script>