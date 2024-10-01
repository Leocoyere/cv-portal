<script>
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

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
			If you're here, it means my QR code caught your attention, and I'm glad! First of all, I hope you're enjoying your time at Disneyland Paris.<br>
			<strong>Since this is the place where dreams come true, maybe mine can too?</strong><br>
			I'm a creative person, and I thought this QR code would be a great way to promote my search for a cybersecurity apprenticeship. If you're working in tech or know someone who is, feel free to share this link with your coworkers or friends—it would really help me a lot.<br>
			You can learn more about me by scrolling down. Thanks!
		</p>
		<p class="leading-relaxed text-gray-700 bg-teal-500 bg-opacity-20 p-4 border-l-4 border-teal-500">
			Si vous êtes ici, c'est que mon QR code a attiré votre attention, et j'en suis ravi ! Avant tout, j'espère que vous profitez de votre visite à Disneyland Paris.<br>
			<strong>Puisque c'est le lieu où les rêves deviennent réalité, peut-être que le mien le deviendra aussi ?</strong><br>
			Je suis une personne créative, et je me suis dit que ce QR code serait une bonne façon de promouvoir ma recherche d'alternance en cybersécurité. Si vous travaillez dans le secteur de la technologie ou connaissez quelqu'un qui y est, n'hésitez pas à partager ce lien avec vos collègues ou amis, cela m'aiderait énormément.<br>
			Vous pouvez en apprendre plus sur moi en faisant défiler la page. Merci !
		</p>
	  </section>
	  
	  <div class="max-w-md mx-auto bg-white shadow-lg rounded-lg mt-2">
  
		<!-- Table of Contents Section -->
		<section class="p-6">
		  <h2 class="text-2xl font-bold text-indigo-600">Table of Contents 🇬🇧</h2>
		  <h2 class="text-2xl font-bold text-teal-500">Sommaire 🇫🇷</h2>
		  
		  <ul class="mt-4 space-y-3">
			<!-- English section links -->
			<li>
			  <a href="#about-me" class="text-indigo-600 font-medium hover:underline">
				I - About me
			  </a>
			  <br>
			  <a href="#a-propos-de-moi" class="text-teal-500 font-medium hover:underline">
				I - À propos de moi
			  </a>
			</li>
			<li>
			  <a href="#what-am-i-looking-for" class="text-indigo-600 font-medium hover:underline">
				II - What am I looking for?
			  </a>
			  <br>
			  <a href="#qu-est-ce-que-je-recherche" class="text-teal-500 font-medium hover:underline">
				II - Qu'est-ce que je recherche ?
			  </a>
			</li>
			<li>
			  <a href="#why-choose-me" class="text-indigo-600 font-medium hover:underline">
				III - Why choose me?
			  </a>
			  <br>
			  <a href="#pourquoi-me-choisir" class="text-teal-500 font-medium hover:underline">
				III - Pourquoi me choisir ?
			  </a>
			</li>
			<li>
			  <a href="#learn-more" class="text-indigo-600 font-medium hover:underline">
				IV - Learn more
			  </a>
			  <br>
			  <a href="#en-savoir-plus" class="text-teal-500 font-medium hover:underline">
				IV - En savoir plus
			  </a>
			</li>
		  </ul>
		</section>
	  </div>

	  <!-- Text Content -->
	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold" id="about-me">
			I - About me
		</h2>
		<p class="leading-relaxed text-gray-700">
			For three years, I studied web development during my bachelor’s program, where I gained a variety of skills, including learning several programming languages, developing websites and mobile applications, and understanding UX/UI design and its challenges. I also deepened my knowledge in project management. These skills allowed me to work with frameworks and APIs to create efficient digital solutions tailored to user needs.
			Now, I’m focusing on cybersecurity. For the past year, I’ve been pursuing a Master’s degree specializing in cybersecurity, where I’ve gained expertise in systems and networks, cryptography, and infrastructure and data security. I’ve also explored governance, risk analysis, and key regulatory frameworks.
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold" id="a-propos-de-moi">
			I - À propos de moi
		</h2>
		<p class="leading-relaxed text-gray-700">
			Pendant trois ans, j'ai étudié le développement web dans le cadre d'un bachelor, où j'ai acquis des compétences variées, notamment en langages de programmation, en développement de sites web et d'applications mobiles, ainsi qu'en design UX/UI et ses enjeux. J'ai également approfondi mes connaissances en gestion de projet. Ces compétences m'ont permis d'utiliser des frameworks et des APIs pour créer des solutions digitales efficaces, adaptées aux besoins des utilisateurs.
			Aujourd'hui, je m'intéresse à la cybersécurité. Depuis un an, je poursuis un Master spécialisé dans ce domaine, où je me suis formé sur les systèmes et réseaux, la cryptographie, ainsi que la sécurité des infrastructures et des données. J'ai également découvert la gouvernance, l'analyse des risques et les principales réglementations en vigueur.
		</p>
	  </section>

	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold" id="what-am-i-looking-for">
			II - What am I looking for ?
		  </h2>
		<p class="leading-relaxed text-gray-700">
			I am looking for a one-year cybersecurity apprenticeship, with a schedule of 3 weeks in the company and 1 week at school. I am particularly interested in pentesting, but I also have a strong interest in governance. I am open to exploring different areas because I am naturally curious and enjoy stepping out of my comfort zone to discover new things. I am available to work in the Île-de-France region or fully remotely.
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold" id="qu-est-ce-que-je-recherche">
			II - Qu'est ce que je recherche ?
		</h2>
		<p class="leading-relaxed text-gray-700">
			Je recherche une alternance en cybersécurité d'une durée de 1 an, avec un rythme de 3 semaines en entreprise et 1 semaine à l'école. Je suis particulièrement intéressé par le pentest, mais j'ai également un grand intérêt pour la gouvernance. Je reste ouvert à d'autres domaines, car je suis de nature curieuse et j'aime sortir de ma zone de confort pour découvrir de nouvelles choses. Je peux me déplacer en Île-de-France ou bien travailler entièrement en distanciel.
		</p>
	  </section>

	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold" id="why-choose-me">
			III - Why choose me ?
		  </h2>
		<p class="leading-relaxed text-gray-700">
			After a year of working part-time in a supermarket to pay for my studies, I’m really eager to invest my energy into something I’m passionate about. I learn quickly, and I truly believe I can bring value to a company. But if no one gives me a chance, I can’t prove my worth...
			If you’re looking for an apprentice, I might just be the ideal candidate—plus, we both love Disney!<br>
			<i class="text-gray-500">(Unless your kids dragged you here, of course.)</i>
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold" id="pourquoi-me-choisir">
			III - Pourquoi me choisir ?
		</h2>
		<p class="leading-relaxed text-gray-700">
			Après une année à travailler à temps partiel dans un supermarché pour financer mes études, j’ai vraiment envie de m’investir dans un domaine qui me passionne. J’ai une grande capacité d’apprentissage, et je suis convaincu de pouvoir apporter une réelle valeur à une entreprise. Mais si personne ne me donne ma chance, je ne pourrai jamais prouver ce que je vaux...
			Si vous cherchez un alternant, je suis peut-être le candidat idéal, et puis, nous aimons tous les deux Disney !<br>
			<i class="text-gray-500">(À moins que vos enfants vous aient forcé à venir.)<i/>
		</p>
	  </section>

	  <section class="space-y-4 my-8 p-6">
		<h2 class="text-2xl text-indigo-400 font-semibold" id="learn-more">
			IV - Learn more
		  </h2>
		<p class="leading-relaxed text-gray-700">
			I'm always looking to expand my network, and I firmly believe that opportunities are created through connections. So, if you can’t help me directly but are in the tech industry, let’s connect on <a href="https://www.linkedin.com/in/leocoyere/?utm_source=qr-code&utm_medium=print&utm_campaign=disney-qr">LinkedIn</a>!
		</p>
		<h2 class="text-2xl text-teal-400 font-semibold" id="en-savoir-plus">
			IV - En savoir plus
		</h2>
		<p class="leading-relaxed text-gray-700">
			Je cherche toujours à étendre mon réseau, et je suis convaincu que c’est à travers les rencontres que se créent les opportunités. Donc, si vous ne pouvez pas m’aider directement, mais que vous travaillez dans le milieu de la tech, connectons-nous sur <a href="https://www.linkedin.com/in/leocoyere/?utm_source=qr-code&utm_medium=print&utm_campaign=disney-qr">LinkedIn</a> !
		</p>
	  </section>
  
	</div>
  
  </section>

<style>
</style>