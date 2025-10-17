<svelte:head>
	<title>Native Technologies — Product Development Partner</title>
	<meta name="description" content="Native Technologies is your product development partner. We design, build, and scale modern web and mobile products." />
	<meta property="og:title" content="Native Technologies — Product Development Partner" />
	<meta property="og:description" content="We design, build, and scale modern web and mobile products." />
	<meta property="og:type" content="website" />
	<meta property="og:site_name" content="Native Technologies" />
	<meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<header class="site-header">
	<div class="inner">
		<div class="brand">
			<span class="brand-mark" aria-hidden="true">{@html `<svg width="100%" height="100%" viewBox="0 0 2705 1745" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M774.012 42.2292L884.239 42.2292L110.512 1702.05L0.000623465 1702.05L774.012 42.2292Z" fill="#11A8AB"/>
<path d="M774.012 42.2292L884.239 42.2292L110.512 1702.05L0.000623465 1702.05L774.012 42.2292Z" fill="#11A8AB"/>
<path d="M2593.75 42.2218L2703.94 42.2218L1930.49 1701.75L1820.01 1701.75L2593.75 42.2218Z" fill="#11A8AB"/>
<path d="M2593.75 42.2218L2703.94 42.2218L1930.49 1701.75L1820.01 1701.75L2593.75 42.2218Z" fill="#11A8AB"/>
<path d="M1046.01 42.2617L1156.34 42.2617L1930.33 1702L1820.01 1702L1046.01 42.2617Z" fill="#11A8AB"/>
<path d="M910.012 42.2617L1020.34 42.2617L1794.33 1702L1684.01 1702L910.012 42.2617Z" fill="#E48526"/>
<path d="M774.012 42.2617L884.34 42.2617L1658.33 1702L1548.01 1702L774.012 42.2617Z" fill="#11A8AB"/>
</svg>`}</span>
			<span>Native Technologies</span>
		</div>
		<nav aria-label="Primary"></nav>
	</div>
</header>

<main>
	<section class="hero section">
		<div class="inner">
			<div class="copy">
				<div class="hero-eyebrow">Product Development</div>
				<h1 class="hero-title">We build reliable, scalable software products</h1>
				<p class="hero-subtitle">We partner with startups and enterprises to design, build, and scale web and mobile products using modern technologies. From idea to production, we deliver with craftsmanship and speed.</p>
				<!-- <div class="hero-ctas">
					<a class="btn" href="#contact">Contact us</a>
					<a class="btn btn--secondary" href="#services">Our services</a>
				</div> -->
			</div>
			<div class="art" aria-hidden="true">
				{@html `<svg viewBox="0 0 400 300" width="100%" height="100%">
					<defs><linearGradient id="g" x1="0" x2="1"><stop offset="0%" stop-color="#22d3ee" /><stop offset="100%" stop-color="#a78bfa" /></linearGradient>
					</defs><circle cx="120" cy="140" r="80" fill="url(#g)" opacity="0.25" />
					<rect x="180" y="80" width="140" height="140" rx="24" fill="url(#g)" opacity="0.2" /></svg>`}
			</div>
		</div>
	</section>

	<section id="services" class="features section">
		<div class="grid">
			<article class="feature-card">
				<h3>Product discovery</h3>
				<p>Rapid prototyping, user research, and roadmapping to validate the right product.</p>
			</article>
			<article class="feature-card">
				<h3>Design & build</h3>
				<p>Modern web and mobile development with SvelteKit, TypeScript, Node.js, and cloud.</p>
			</article>
			<article class="feature-card">
				<h3>Scale & operate</h3>
				<p>Performance, observability, CI/CD, and cloud infrastructure for reliable operations.</p>
			</article>
		</div>
	</section>

	<section id="contact" class="contact section">
		<div class="panel">
			<div>
				<h2>Let’s talk</h2>
				<p class="muted">Have a product idea or need an experienced team to accelerate delivery? Reach out and we’ll get back within one business day.</p>
			</div>
			<div class="methods">
				<div>
					<strong>Email</strong>
					<div><a href="mailto:admin@nativetechnologies.my">admin@nativetechnologies.my</a></div>
				</div>
				<div>
					<strong>Phone</strong>
					<div><a href="tel:+601167435688">+60 11 6743 5688</a></div>
				</div>
			</div>
		</div>
	</section>

	<footer class="site-footer">
		<div class="inner">
			<div>© {new Date().getFullYear()} Native Technologies 202303002677 (KT0537367-W). All Rights Reserved.</div>
			<!-- <div>Built with SvelteKit</div> -->
		</div>
	</footer>
</main>
