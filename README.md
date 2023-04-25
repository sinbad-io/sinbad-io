<link href='https://fonts.googleapis.com/css?family=Roboto' rel='stylesheet'>

<div>
	<style>
		body {
			overflow: hidden;
		}
		svg {
			font-family: 'Roboto';
			width: 100%; height: 200px;
		}
		svg text {
			animation: stroke 5s infinite alternate;
			stroke-width: 2;
			text-align: center;
			stroke: #365fa0;
			font-size: 130px;
		}
		.header {
			height: 200px;
			background: url(https://wearecollins.imgix.net/uploads/RH_COLLINS_Web_23-e96d6c.jpg?auto=format%2Ccompress&dpr=2&fit=max&q=90&w=1500);
			background-size: cover;
			text-align: center;
			align-items: center;
			justify-content: center;
			display: flex;
			width: 100%;
		}
		@keyframes stroke {
			0%   {
				fill: #E5FF95; stroke: #ADE61E;
				stroke-dashoffset: 25%; stroke-dasharray: 0 50%; stroke-width: 2;
			}
			70%  {fill: #E5FF95; stroke: #ADE61E; }
			80%  {fill: #E5FF95; stroke: #ADE61E; stroke-width: 3; }
			100% {
				fill: white; stroke: white; 
				stroke-dashoffset: -25%; stroke-dasharray: 50% 0; stroke-width: 0;
			}
		}
	</style>
	<div class="header">
		<svg viewBox="-230 -80 1000 100">
			<text>
				Sinbad-io
			</text>
		</svg>
	</div>
</div>

<br/> <br/>

# Welcome 👋

<img src="https://github-readme-stats.vercel.app/api?username=sinbad-io&show_icons=true&count_private=true" align="right" />

I author and maintain open source projects written in Golang. I care deeply about running, literature, phyiscs, ownership and intrastructure.

In 2022 I co-founded Nuntio, a Dasnish software company building an open-source backend and deployment platform on Kubernetes, providing the ease-of-use of traditional platforms like Firebase, with the flexibility and complexity provided by Kubernetes.

