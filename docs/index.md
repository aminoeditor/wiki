<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [{
	avatar: 'https://avatars.githubusercontent.com/u/1380218?v=4',
	name: 'Timothy Long',
	title: 'Creator/Designer',
	links: [
		{ icon: 'github', link: 'https://github.com/timothylong' },
	]
},{
	avatar: 'https://avatars.githubusercontent.com/u/3223296?v=4',
	name: 'Eric Uldall',
	title: 'Creator/Engineer',
	links: [
		{ icon: 'github', link: 'https://github.com/ericuldall' },
	]
}]
</script>

# Our Team

Say hello to our awesome team.

<VPTeamMembers size="small" :members="members" />
