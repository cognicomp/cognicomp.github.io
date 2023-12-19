<script type="text/javascript">
function submit(e) {
  e.preventDefault()
  setTimeout(() => {window.location = "https://cognicomp.github.io/thank-you.html"}, 800);
}
</script>

# Contact

Contact us via the form below and we'll get in touch as soon as possible.

<form onsubmit="submit()">
<p>
  <label for="email">Your Email</label><br>
  <input type="text" id="email">
</p>
<p>
<label for="name">Your Name</label><br>
<input type="text" id="name">
</p>
<p>
<label for="message">Message</label><br>
<textarea id="message" rows="10" cols="80"></textarea>
</p>
<input type="submit">
</form>

<br>
<br>