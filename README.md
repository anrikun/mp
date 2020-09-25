# MP3 MediaRecorder Polyfill

A MediaRecorder polyfill (for Safari) with MP3 encoding support

## Usage

```
<script>
if (!window.MediaRecorder) {
  document.write(decodeURI('%3Cscript defer src="/path/to/dist/polyfill.js">%3C/script>'));
}
</script>
