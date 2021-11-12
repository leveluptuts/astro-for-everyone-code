<script lang="ts">
  export let url;
  let playbackRate = 1;
</script>

<audio bind:playbackRate src={url} controls />
<select bind:value={playbackRate} name="playback" id="playback">
  <option value={1}>1</option>
  <option value={1.5}>1.5</option>
  <option value={2}>2</option>
</select>
