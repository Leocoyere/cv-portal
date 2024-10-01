<script>
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<!-- <section class="mx-4">
	<h1 class="text-4xl text-left my-8 md:text-5xl leading-10 ">
		🇬🇧 Welcome! <br>
		🇫🇷 Bienvenue !
	</h1>
	<p class="my-4">🇬🇧 Vivamus maximus libero et sodales ultrices. Nunc blandit, nibh eget laoreet rutrum, lorem felis semper justo, sit amet suscipit sem purus vel mauris. Nam rhoncus scelerisque mollis. Pellentesque sed justo in massa iaculis ullamcorper. Maecenas dignissim ligula ex, vel mattis justo fringilla non. Praesent sollicitudin convallis libero, feugiat luctus ex fringilla vitae. Duis pulvinar vestibulum eleifend.</p>
	<p class="my-4">🇫🇷 Vivamus maximus libero et sodales ultrices. Nunc blandit, nibh eget laoreet rutrum, lorem felis semper justo, sit amet suscipit sem purus vel mauris. Nam rhoncus scelerisque mollis. Pellentesque sed justo in massa iaculis ullamcorper. Maecenas dignissim ligula ex, vel mattis justo fringilla non. Praesent sollicitudin convallis libero, feugiat luctus ex fringilla vitae. Duis pulvinar vestibulum eleifend.</p>

</section> -->
<section class="bg-gray-100 text-gray-900 font-sans">

	<!-- Main Container -->
	<div class="max-w-md mx-auto bg-white shadow-lg rounded-lg mt-10">
	  
	  <!-- Title Section -->
	  <header class="mb-3 p-6">
		<h1 class="text-4xl font-bold text-indigo-600">Welcome! 🇬🇧</h1>
		<h1 class="text-4xl font-bold text-teal-500">Bienvenue ! 🇫🇷</h1>
		<p class="mt-3 text-sm text-gray-500">🇬🇧 You speak english?<br> Focus on the <span class="text-indigo-600">indigo</span></p>
		<p class="mt-1 text-sm text-gray-500">🇫🇷 Vous parlez français ?<br> Concentrez vous sur le <span class="text-teal-500">turquoise</span></p>
	  </header>
	  
	  <section class="space-y-4 my-4">
		<p class="leading-relaxed text-gray-700 bg-indigo-600 bg-opacity-20 p-4 border-l-4 border-indigo-600">
			If you are here, it means my QR code caught your attention, I'm glad! First of all I hope you are enjoying your journey at Disneyland Paris.<br>
			<strong>Since it's the land were dreams comes true, maybe mine can too?</strong><br>
			I'm a creative person, so I though the QR would be a good way of promoting my research.
			I'm looking for an apprenticeship in cybersecurity. If you're working in tech or know someone who does, feel free to share this link to your coworkers / friends, it will really help me a lot.<br>
			You can learn more about me by scrolling down. Thanks!
		</p>
		<p class="leading-relaxed text-gray-700 bg-teal-500 bg-opacity-20 p-4 border-l-4 border-teal-500">
			Si vous êtes là, c'est que mon QR code à attiré votre attention. J'en suis ravi ! Tout d'abord, j'espère que vous passez un bon séjour à Disneyland Paris.<br>
			<strong>Puisque c'est l'endroit où les rêves se réalisent peut-être que le mien peut devenir réalité ?</strong><br>
			Je suis quelqu'un de créatif, alors j'ai pensé que le QR serait un bon moyen de promouvoir ma recherche.
			Je recherche une alternance en cybersécurité. Si vous travaillez dans l'informatique ou que vous connaissez quelqu'un qui y travaille, n'hésitez pas à partager ce lien avec vos collègues / amis, ça m'aide beaucoup.<br>
			Vous en apprendrez plus sur moi en visitant ce site. Merci !
		</p>
	  </section>
	  
	  <!-- Text Content -->
	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold">
			I - About me
		</h2>
		<p class="leading-relaxed text-gray-700">
		  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur vehicula, nulla id ultrices faucibus, lorem sapien convallis lectus, in vestibulum orci orci at nibh. Sed tempor erat eu ante tincidunt, ac egestas leo dignissim.
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold">
			I - À propos de moi
		</h2>
		<p class="leading-relaxed text-gray-700">
			Pendant 3 ans, j'ai étudié le développement web au cours d'un bachelor, j'ai acquis des compétences variées, notamment l'apprentissage de divers langages de programmation, le développement de sites web et d'applications mobiles, ainsi que le design UX/UI et ses enjeux. J'ai également approfondi mes connaissances en gestion de projet. Mes compétences m'ont permi d'utiliser des frameworks et APIs pour créer des solutions digitales efficaces et adaptées aux besoins des utilisateurs. Maintenant je m'intéresse à la cybersécurité, depuis 1 an je suis en Master spécialisé dans la cybersécurité. Je me suis formé sur les systèmes et réseaux mais également sur la cryptographie et la sécurité des infrastructures et des données. J'ai aussi pu découvrir la gouvernance, l'analyse des risques et les réglementations existantes.
		</p>
	  </section>

	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold">
			II - What am I looking for ?
		  </h2>
		<p class="leading-relaxed text-gray-700">
		  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur vehicula, nulla id ultrices faucibus, lorem sapien convallis lectus, in vestibulum orci orci at nibh. Sed tempor erat eu ante tincidunt, ac egestas leo dignissim.
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold">
			II - Qu'est ce que je recherche ?
		</h2>
		<p class="leading-relaxed text-gray-700">
			Je recherche une alternance en cybersécurité pour une durée de 1 an. Mon rythme est de 3 semaines en entreprise et 1 semaine à l'école. Je suis principalement intéressé par le pentest mais j'ai aussi beaucoup d'intêret pour la gouvernance. Je suis un peu ouvert à tout car je suis de nature curieux et j'aime sortir de ma zone de confort et découvrir de nouvelles choses.
		</p>
	  </section>

	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold">
			III - Why choose me ?
		  </h2>
		<p class="leading-relaxed text-gray-700">
		  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur vehicula, nulla id ultrices faucibus, lorem sapien convallis lectus, in vestibulum orci orci at nibh. Sed tempor erat eu ante tincidunt, ac egestas leo dignissim.
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold">
			III - Pourquoi me choisir ?
		</h2>
		<p class="leading-relaxed text-gray-700">
			Après 1 an à travailler à temps partiel dans un supermarché pour payer mes études, j'ai vraiment envie de m'investir dans quelque chose qui m'intéresse. J'ai une forte capacité d'apprentissage alors je pense vraiment pouvoir être utile en entreprise. Mais si personne ne me laisse ma chance, je ne peux pas prouver ma valeur...
			Si vous recherchez un alternant je suis peut-être le candidat idéal, en plus on aime tout les deux Disney !<br>
			<i class="text-gray-500">( À part si vos enfants vous on forcé à venir )<i/>
		</p>
	  </section>

	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold">
			IV - Extra
		  </h2>
		<p class="leading-relaxed text-gray-700">
			Je recherche toujours à étendre mon réseau et je suis persuadé que c'est au travers des connaissances que les opportunité se créent, alors si vous ne pouvez pas m'aider mais que vous êtes lié au milieu de la tech, connectons nous sur <a href="https://www.linkedin.com/in/leocoyere/">LinkedIn</a> !
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold">
			IV - Extra
		</h2>
		<p class="leading-relaxed text-gray-700">
		  Pellentesque habitant morbi <a href="" class="coral-500">tristique</a> senectus et netus et malesuada fames ac turpis egestas. Praesent ut malesuada metus, vel dapibus orci. Mauris eget ullamcorper sapien, id posuere nisl.
		</p>
	  </section>
  
	  <!-- Footer (Optional) -->
	  <!-- <footer class="mt-8 text-center">
		<p class="text-sm text-gray-400">© 2024 My Website. All rights reserved.</p>
	  </footer> -->
  
	</div>
  
  </section>

<style>
</style>