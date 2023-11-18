<script>
    import Fa from "svelte-fa";
    import { faPhone } from "@fortawesome/free-solid-svg-icons";

    const value = (node, param) => node.setAttribute('value', param);
    const addVendorTest = async (event) => {
        const formData = new FormData(event.target)

        // [Use formData]
        console.log([...formData]);

        event.target.reset();
    }
</script>

<main>
    <div class="container">
        <div class="card">
            <div class="card-content">
                <h1>Contattami</h1>
            </div>
            <form class="card-form">
                <div class="input">
                    <input type="text" class="input-field" required/>
                    <!-- svelte-ignore a11y-label-has-associated-control -->
                    <label class="input-label">Nome e Cognome</label>
                </div>
                            <div class="input">
                    <input type="text" class="input-field" required/>
                    <!-- svelte-ignore a11y-label-has-associated-control -->
                    <label class="input-label">Email</label>
                </div>
                <div class="action">
                    <button class="action-button">Invia</button>
                </div>
            </form>
        </div>
    </div>
</main>

<style>
    @import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&display=swap');

    input {
        appearance: none;
        border-radius: 0;
    }

    .icon {
        color: #a8dadc;
        display: flex;
        align-items: center;
    }

    .card-content {
        flex-direction: column;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .container {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .card {
        margin: 3rem;
        display: flex;
        flex-direction: column;
        height: 100%;
        width: 100%;
        max-width: 425px;
        border-radius: 10px;
        background-color:#1c1d1d;
        box-shadow:#959da533 0 8px 24px;
        padding: .75rem;
        padding-left: 1.5rem;
        padding-right: 1.5rem;
        padding-bottom: 4.5rem;
    }

    .card-form {
        padding: 2rem 1rem 0;
    }

    .input {
        display: flex;
        flex-direction: column-reverse;
        position: relative;
        padding-top: 1.5rem;
        &+.input {
            margin-top: 1.5rem;
        }
    }

    .input-label {
        color: #a8dadc;
        position: absolute;
        top: 1.5rem;
        transition: .25s ease;
    }

    .input-field {
        color: #a8dadc;
        border: 0;
        z-index: 1;
        background-color: transparent;
        border-bottom: 2px solid #a8dadc;
        font: inherit;
        font-size: 1.125rem;
        padding: .25rem 0;
        &:focus, &:valid {
            outline: 0;
            border-bottom-color: #a8dadc;
            &+.input-label {
                color: #a8dadc;
                transform: translateY(-1.5rem);
            }
        }
    }

    .action {
        margin-top: 2rem;
    }

    .action-button {
        font: inherit;
        font-size: 1.25rem;
        padding: 1em;
        width: 100%;
        font-weight: 500;
        background-color: #58a6d3;
        border-radius: 6px;
        color: #FFF;
        border: 0;
        &:focus {
            outline: 0;
        }
    }
</style>
