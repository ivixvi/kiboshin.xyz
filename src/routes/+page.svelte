<script lang="ts">
	import KobochanCube from '../lib/KobochanCube.svelte';
</script>

<h1>Welcome to kiboshin kingdom!</h1>

<KobochanCube/>

<nobr><table border="0" cellspacing="0" cellpadding="0"><tbody><tr><td><a href="https://www.free-counter.jp/"><img src="https://www.f-counter.net/ani1/62/1686281428/" alt="アクセスカウンター" border="0" style="margin:0px; padding:0px; border:0px; vertical-align:bottom"></a></td>
<td><a href="https://www.free-counter.jp/"><img src="https://www.f-counter.net/ani2/62/1686281428/" alt="アクセスカウンター" border="0" style="margin:0px; padding:0px; border:0px; vertical-align:bottom"></a></td></tr></tbody></table></nobr>

<style>
.box1{
  animation:3s linear infinite rotation;
}
@keyframes rotation{
  0%{ transform:rotate(0);}
  100%{ transform:rotate(360deg); }
}
</style>