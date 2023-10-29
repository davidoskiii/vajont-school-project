<script>
    import { theme } from '../theame.js';

    let isDarkMode = $theme === 'dark';

    function toggleTheme() {
        $theme = isDarkMode ? 'light' : 'dark';
        isDarkMode = !isDarkMode;
    }
</script>

<main>
    <div class='toggle-switch'>
        <label>
            <input type="checkbox" bind:checked={isDarkMode} on:change={toggleTheme}>
            <span class='slider'></span>
        </label>
    </div>
</main>

<style>

</style>