<script>
	import Panel from '$components/Panel.svelte';
	import Header from '$components/Header.svelte';
	import OfferingSection from '$components/OfferingSection.svelte';
</script>

<Panel className="my-32">
	<Header>WHAT I CAN DO FOR YOU</Header>

	<div id="offerings" class="mt-32 flex flex-col gap-10 md:flex-row">
		<OfferingSection heading="WEB DEVELOPMENT">
			<i slot="icon" class="fa-sharp fa-thin fa-code text-7xl"></i>

			<p>
				More than 25 years of experience in web development, through multiple languages, platforms
				and libraries.
			</p>

			<p>
				Extensive experience with frontend and backend development, including HTML, CSS, React,
				JavaScript, TypeScript, NodeJS, Golang, PHP, Postgres, MySQL and others.
			</p>
		</OfferingSection>

		<OfferingSection heading="BLOCKCHAIN DEVELOPMENT">
			<i slot="icon" class="fa-sharp fa-thin fa-code-branch text-7xl"></i>

			<p>
				Web3 development, including smart contracts, dApps, and more. Web3 integration with existing
				smart contracts. Auditing and testing of existing smart contract projects. Tokenisation of
				Real World Assets and implementation of NFTs.
			</p>

			<p>Development of blockchain projects in Solidity, DAML, and Hedera Hashgraph.</p>
		</OfferingSection>

		<OfferingSection heading="TECHNICAL WRITING">
			<i slot="icon" class="fa-sharp fa-thin fa-pen-nib text-7xl"></i>

			<p>
				Highly skilled technical writer with a focus on web development aimed at newer developers.
				As well as writing for documetation of projects and processes in a commercial sense also run
				a successful Medium account for many years on a variety of mostly development-related
				topics, with regular readers and tens of thousands of views.
			</p>
		</OfferingSection>
	</div>
</Panel>
