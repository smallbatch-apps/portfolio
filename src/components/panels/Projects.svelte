<script>
	import Panel from '$components/Panel.svelte';
	import Header from '$components/Header.svelte';
	import Tag from '$components/Tag.svelte';
	import SocialButton from '$components/SocialButton.svelte';
</script>

<div id="projects" class="mx-auto my-32 w-3/4">
	<Panel>
		<Header>FEATURED PROJECTS</Header>

		<div class="mt-20 flex flex-col justify-center gap-10 font-thin leading-loose">
			<div class="flex gap-10">
				<div class="w-96 flex-shrink-0">
					<img
						src="images/screenshot/yield-app-screenshot.png"
						class="w-96 rounded border"
						alt="Yield App v3"
					/>
				</div>
				<div class="flex flex-col gap-4">
					<h2 class="text-2xl font-semibold tracking-widest text-red-400">Yield App V3</h2>

					<p>
						Commercial production cryptocurrency trading platform. My primary contribution was the
						development of the base platform for V3, an upgrade to add Tailwind, TypeScript, and
						NextJS support. This is achieved with a unique design system integrated into a custom
						component library, accompanied by comprehensive StoryBook component documentation and
						more than 4,000 unit and integration tests.
					</p>

					<p>
						Unfortunately Yield App went into liquidation in July 2024 and its source code is not
						open.
					</p>

					<div class="flex gap-2">
						<Tag variant="frontend">NextJS</Tag>
						<Tag variant="frontend">React</Tag>
						<Tag variant="frontend">TypeScript</Tag>
						<Tag variant="frontend">Storybook</Tag>
						<Tag variant="frontend">Testing</Tag>
						<Tag variant="backend">NodeJS</Tag>
						<Tag variant="blockchain">WEB3</Tag>
					</div>
				</div>
			</div>

			<div class="flex gap-10">
				<div class="w-96 flex-shrink-0">
					<img
						src="images/screenshot/water-ledger-screenshot.png"
						class="w-96 rounded border"
						alt="Water Ledger"
					/>
				</div>
				<div class="flex flex-col gap-4">
					<h2 class="text-2xl font-semibold tracking-widest text-red-400">Water Ledger</h2>

					<p>
						Blockchain-based water trading system for publicly traded water schemes. I was
						responsible for the development of the vast majority of the code, backend and frontend,
						and also a comprehensive rewrite of all Solidity smart contracts. Also implemented a
						unique backend architecture creating an <a
							class="text-amber-600 underline decoration-dashed underline-offset-4 hover:text-amber-700"
							href="https://medium.com/civic-ledger/event-sourcing-for-public-ethereum-applications-eb9bea90a962"
							>Event Sourcing for Ethereum</a
						> pattern.
					</p>

					<div>
						<SocialButton
							variant="white"
							size="small"
							url="https://github.com/civicledger/waterledger-contracts"
						>
							<i class="fa-brands fa-github"></i> Contracts
						</SocialButton>

						<SocialButton
							variant="white"
							size="small"
							url="https://github.com/civicledger/waterledger-dashboard"
						>
							<i class="fa-brands fa-github"></i> Frontend
						</SocialButton>
					</div>

					<div class="flex gap-2">
						<Tag variant="frontend">React</Tag>
						<Tag variant="frontend">TypeScript</Tag>
						<Tag variant="backend">NodeJS</Tag>
						<Tag variant="backend">PostgreSQL</Tag>
						<Tag variant="blockchain">Solidity</Tag>
						<Tag variant="blockchain">WEB3</Tag>
						<Tag variant="blockchain">TESTING</Tag>
					</div>
				</div>
			</div>

			<div class="flex gap-10">
				<div class="w-96 flex-shrink-0">
					<img
						src="images/screenshot/earnsmart-screenshot2.png"
						class="w-96 rounded border"
						alt="Water Ledger"
					/>
				</div>
				<div class="flex flex-col gap-4">
					<h2 class="text-2xl font-semibold tracking-widest text-red-400">EarnSmart</h2>

					<p>
						Written in Golang for performance and concurrency. The database is a hybrid between
						Postgres for standard relational data and TigerBeetle, a high performance transaction
						mechanism with built in double-entry storage and logged balances. It is deliberately
						missing key systems, such as a "hot wallet" and integration with RFQ providers for
						swaps. There are also no rules around fees.
					</p>
					<p>
						Frontend is a simple NextJS application intended to demonstrate the functionality of the
						backend.
					</p>

					<div>
						<SocialButton
							variant="white"
							size="small"
							url="https://github.com/smallbatch-apps/earnsmart-api"
						>
							<i class="fa-brands fa-github"></i> Backend
						</SocialButton>

						<SocialButton
							variant="white"
							size="small"
							url="https://github.com/smallbatch-apps/earnsmart-frontend"
						>
							<i class="fa-brands fa-github"></i> Frontend
						</SocialButton>
					</div>

					<div class="flex gap-2">
						<Tag variant="frontend">NextJS</Tag>
						<Tag variant="frontend">React</Tag>
						<Tag variant="frontend">TypeScript</Tag>
						<Tag variant="backend">Golang</Tag>
						<Tag variant="backend">PostgreSQL</Tag>
						<Tag variant="backend">TigerBeetle</Tag>
					</div>
				</div>
			</div>

			<div class="flex gap-10">
				<div class="w-96 flex-shrink-0">
					<img
						src="images/screenshot/catan-screenshot.png"
						class="w-96 rounded border"
						alt="Blockchain Catan"
					/>
				</div>
				<div class="flex flex-col gap-4">
					<h2 class="text-2xl font-semibold tracking-widest text-red-400">Blockchain Catan</h2>

					<p>
						Solidity smart contracts represent the board state and enforce game mechanics. Resources
						are handled using the IEP-1155 multi-token spec. The application is scaffolded and
						extensively tested using Foundry.
					</p>
					<p>
						The overall design is based on mathematical Graph Theory, making each settlement
						location a "node" and each hexagon side an "edge". Frontend is currently under active
						development, and is a simple React application to view board state.
					</p>

					<div>
						<SocialButton
							variant="white"
							size="small"
							url="https://github.com/smallbatch-apps/foundry-catan"
						>
							<i class="fa-brands fa-github"></i> Contracts
						</SocialButton>

						<!-- <SocialButton
							variant="white"
							size="small"
							url="https://github.com/smallbatch-apps/foundry-catan"
						>
							<i class="fa-brands fa-github"></i> Frontend
						</SocialButton> -->
					</div>

					<div class="flex gap-2">
						<Tag variant="frontend">React</Tag>
						<Tag variant="frontend">TypeScript</Tag>
						<Tag variant="blockchain">Testing</Tag>
						<Tag variant="blockchain">Solidity</Tag>
						<Tag variant="blockchain">WEB3</Tag>
					</div>
				</div>
			</div>
		</div>
	</Panel>
</div>
