<script>
    import Fa from 'svelte-fa'
    import { faGithub } from '@fortawesome/free-brands-svg-icons';
    import { faInstagram } from '@fortawesome/free-brands-svg-icons';
    import { faDiscord } from '@fortawesome/free-brands-svg-icons';
</script>

<main>
    <footer>
        <div class="footer-content">
            <div class="footer-text">
                <h1>Support</h1>
                <p>For questions and problems send an email to davide.mascherin9@gmail.com</p>
            </div>
            <div class="footer-contacts">
                <div class="footer-icons">
                    <a href="https://github.com/davidoskiii/vajont-school-project"><Fa size="1.5x" icon={faGithub}/></a>
                    <a href="https://www.instagram.com/_davidoskiii/"><Fa size="1.5x" icon={faInstagram}/></a>
                    <a href="/"><Fa size="1.5x" icon={faDiscord}/></a>
                </div>
            </div>
            <div class="footer-bottom">
                <p>Copyright &copy;2020 _davidoskiii. Designed by <span>davide mascherin</span></p>
            </div>
        </div>
    </footer>
</main>

<style>

</style>
