<script>
	import profileImage from '../images/profile_image.jpg';
	import bdaoImage from '../images/BostonDAOlogo.jpg';
	import ethBostonLogo from '../images/ethBostonLogo.png';
	import mitBTCExpoLogo from '../images/mitBTCExpoLogo.png';
	import lbLogo from '../images/LB_Logo_Dark.jpg';
</script>

<footer class="bg-slate-900 text-white py-8 px-4 mt-20">
	<div
		class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-start md:items-center gap-8"
	>
		<!-- Profile Section -->
		<div class="flex flex-col items-center space-y-4 profile-card md:items-start md:flex-1">
			<div class="flex items-center space-x-4">
				<img
					src={profileImage}
					alt="Mike Abramo"
					class="w-16 h-16 rounded-full border-2 border-violet-400"
				/>
				<div>
					<h3 class="font-bold text-lg">Mike Abramo</h3>
					<p class="text-sm text-gray-400">If it's not decentralized, it's not crypto.</p>
				</div>
			</div>
			<div class="icon-container">
				<div class="icon-item">
					<a href="https://mitbitcoinexpo.org/" target="_blank">
						<img
							src={mitBTCExpoLogo}
							alt="MIT Bitcoin Expo"
							class="w-16 h-16 rounded-full border-2 border-violet-400"
						/>
					</a>
					<p>MIT BTC<br /> Expo</p>
				</div>
				<div class="icon-item">
					<a href="https://www.ethboston.xyz/" target="_blank">
						<img
							src={ethBostonLogo}
							alt="Boston DAO"
							class="w-16 h-16 rounded-full border-2 border-violet-400"
						/>
					</a>
					<p>ETH<br /> Boston</p>
				</div>
				<div class="icon-item">
					<a href="https://x.com/thebostondao" target="_blank">
						<img
							src={bdaoImage}
							alt="Boston DAO"
							class="w-16 h-16 rounded-full border-2 border-violet-400"
						/>
					</a>
					<p>Boston<br /> DAO</p>
				</div>
				<div class="icon-item">
					<a href="https://www.lightningbounties.com/" target="_blank">
						<img
							src={lbLogo}
							alt="Lightning Bounties"
							class="w-16 h-16 rounded-full border-2 border-violet-400"
						/>
					</a>
					<p>Lightning<br /> Bounties</p>
				</div>
			</div>
		</div>

		<!-- Navigation Links -->
		<div class="space-y-4 text-center md:flex-1">
			<h4 class="text-lg font-semibold mb-4 text-violet-400">Quick Links</h4>
			<nav class="flex flex-col space-y-2">
				<a href="#projects" class="hover:text-violet-400 transition-colors"
					><i class="fa-solid fa-code mr-2" />Projects</a
				>
				<a href="#about" class="hover:text-violet-400 transition-colors"
					><i class="fa-regular fa-circle-user mr-2" /> About</a
				>
				<a
					href="https://blog.lightningbounties.com/"
					class="hover:text-violet-400 transition-colors"
					><i class="fa-solid fa-pencil mr-2" /> Blog</a
				>
			</nav>
		</div>

		<!-- Social Links -->
		<div class="space-y-4 text-align md:flex-1">
			<h4 class="text-lg font-semibold mb-4 text-violet-400">Connect</h4>
			<div class="flex flex-col space-y-2">
				<a
					href="https://github.com/SonnyMonroe"
					target="_blank"
					class="flex items-center hover:text-violet-400 transition-colors"
				>
					<i class="fa-brands fa-github mr-2" /> GitHub
				</a>
				<a
					href="https://www.linkedin.com/in/michael-abramo/"
					target="_blank"
					class="flex items-center hover:text-violet-400 transition-colors"
				>
					<i class="fa-brands fa-linkedin mr-2" /> LinkedIn
				</a>
				<a
					href="mailto:mabramo11@protonmail.com"
					class="flex items-center hover:text-violet-400 transition-colors"
				>
					<i class="fa-solid fa-envelope mr-2" /> Email
				</a>
			</div>
		</div>
	</div>

	<!-- Copyright -->
	<div class="mt-8 pt-8 border-t border-gray-800 text-center text-sm text-gray-400">
		<p>&copy; {new Date().getFullYear()} Mike Abramo. All rights reserved.</p>
	</div>
</footer>

<style>
	.profile-card {
		border: 2px solid #7c3aed; /* violet-400 */
		box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
		padding: 1rem;
		border-radius: 0.5rem;
		background-color: #1e293b; /* slate-900 */
		width: 100%;
	}
	.icon-container {
		display: flex;
		justify-content: space-between;
		margin-top: 1rem;
		width: 100%;
	}
	.icon-item {
		display: flex;
		flex-direction: column;
		align-items: center;
		text-align: center;
		margin: 0.5rem;
	}
	.icon-item img {
		display: flex;
		width: 40px;
		height: 40px;
	}
	.icon-item p {
		margin-top: 0.5rem;
		font-size: 0.75rem;
		color: #9ca3af; /* gray-400 */
		line-height: 1; /* Adjust line height to reduce spacing */
	}
</style>
