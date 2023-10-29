
<script context="module">
    import Fa from 'svelte-fa'
    import { faInfo } from '@fortawesome/free-solid-svg-icons';

    export let message;

    export function showToast(message, duration) {
        const toastBox = document.getElementById('toast-box');
        if (toastBox) {
            const toast = document.createElement('div');
            toast.classList.add('toast');
            toast.innerHTML = '<svg class="svg-icon" xmlns="http://www.w3.org/2000/svg" height="1.5em" viewBox="0 0 512 512"><style>svg{fill:#a8dadc;}</style><path d="M256 512A256 256 0 1 0 256 0a256 256 0 1 0 0 512zM369 209L241 337c-9.4 9.4-24.6 9.4-33.9 0l-64-64c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0l47 47L335 175c9.4-9.4 24.6-9.4 33.9 0s9.4 24.6 0 33.9z"/></svg>' + message;
            toastBox.appendChild(toast);

            setTimeout(() => {
                toast.remove()
            }, duration)
        }
    }
</script>

<main>
    <div id="toast-box"></div>
</main>

<style>
    /* Add your toast styles here */
</style>



