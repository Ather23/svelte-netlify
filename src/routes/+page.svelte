<script>
	import '../app.css';
</script>

<div class="min-h-screen flex flex-col bg-gray-50">
	<header class="bg-teal-500 text-white py-6">
		<div class="container mx-auto px-4">
			<h1 class="text-3xl font-bold">AtoZ Psychotherapy</h1>
			<p class="mt-2">Your tagline or short description</p>
		</div>
	</header>

	<main class="flex-grow container mx-auto px-4 py-8">
		<section id="about" class="py-16">
			<h2 class="text-2xl font-bold mb-4 text-teal-700">About Me</h2>
			<p class="text-gray-700">Description about the therapist.</p>
		</section>

		<section id="services" class="py-16 bg-teal-50 rounded-lg flex flex-col items-center">
			<h2 class="text-2xl font-bold mb-4 text-teal-700">Services</h2>
			<div class="space-y-8 w-full max-w-2xl">
				<div class="bg-white p-6 rounded-lg shadow-md">
					<h3 class="text-xl font-semibold mb-2 text-teal-700">Individual Therapy</h3>
					<p class="text-gray-700">One-on-one sessions to help you navigate personal challenges.</p>
				</div>
				<div class="bg-white p-6 rounded-lg shadow-md">
					<h3 class="text-xl font-semibold mb-2 text-teal-700">Couples Therapy</h3>
					<p class="text-gray-700">
						Sessions for couples to improve communication and resolve conflicts.
					</p>
				</div>
				<div class="bg-white p-6 rounded-lg shadow-md">
					<h3 class="text-xl font-semibold mb-2 text-teal-700">Family Therapy</h3>
					<p class="text-gray-700">
						Sessions for families to work through issues and strengthen bonds.
					</p>
				</div>
				<div class="bg-white p-6 rounded-lg shadow-md">
					<h3 class="text-xl font-semibold mb-2 text-teal-700">Group Therapy</h3>
					<p class="text-gray-700">Group sessions to provide support and shared experiences.</p>
				</div>
			</div>
		</section>

		<section id="pricing" class="py-16">
			<h2 class="text-2xl font-bold mb-4 text-teal-700">Pricing Tiers</h2>
			<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
				<div class="bg-white p-6 rounded-lg shadow-md">
					<h3 class="text-xl font-semibold mb-2 text-teal-700">Basic</h3>
					<p class="text-gray-700 mb-4">$50 / session</p>
					<ul class="list-disc pl-5 text-gray-700">
						<li>30-minute session</li>
						<li>Email support</li>
					</ul>
				</div>
				<div class="bg-white p-6 rounded-lg shadow-md">
					<h3 class="text-xl font-semibold mb-2 text-teal-700">Standard</h3>
					<p class="text-gray-700 mb-4">$100 / session</p>
					<ul class="list-disc pl-5 text-gray-700">
						<li>60-minute session</li>
						<li>Email & phone support</li>
					</ul>
				</div>
				<div class="bg-white p-6 rounded-lg shadow-md">
					<h3 class="text-xl font-semibold mb-2 text-teal-700">Premium</h3>
					<p class="text-gray-700 mb-4">$150 / session</p>
					<ul class="list-disc pl-5 text-gray-700">
						<li>90-minute session</li>
						<li>Priority support</li>
					</ul>
				</div>
			</div>
		</section>

		<section id="contact" class="py-16">
			<h2 class="text-2xl font-bold mb-4 text-teal-700">Contact</h2>
			<p class="text-gray-700">Contact information and form.</p>
		</section>
	</main>

	<footer class="bg-teal-600 text-white py-6">
		<div class="container mx-auto px-4">
			<p>&copy; 2024 Therapist Name. All rights reserved.</p>
		</div>
	</footer>
</div>

<style>
	/* Additional styles if needed */
</style>
