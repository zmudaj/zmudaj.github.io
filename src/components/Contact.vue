<template>
    <div class="contact">
        <h2>jasonZmuda.contact = {</h2>
        <div class="container">
            <div class="row">
                <div class="col">
                    <form action="https://formspree.io/zmudakann@gmail.com" method="POST">
                        <input type="text" name="name" placeholder="Your Name">
                        <input type="email" name="_replyto" placeholder="Your email">
                        <textarea name="message" placeholder="Your message"></textarea>
                        <!--<button type="submit" value="Send" class="submitButton #558b2f light-green darken-3">Send</button>-->
                        <button class="btn waves-effect waves-light submitButton" type="submit" name="action">Submit
    <i class="material-icons right">send</i>
  </button>
                    </form>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <p>email: zmudakann@gmail.com,</p>
                    <p>phone: (425) 478-4622</p>
                </div>
            </div>
        </div>
        <h2>};</h2>
    </div>
</template>

<script>
    export default {
        name: 'contact'
    }

</script>

<style>
    .submitButton {
        margin-top: 2%;
    }
</style>