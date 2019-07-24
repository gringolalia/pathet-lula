<template lang="pug">
v-app
	v-toolbar(app='')
		v-toolbar-title.headline.text-capitalize
			span
				i.fas.fa-sun.fa-2x.mr-2
				| Ethereal Unintended Blind


		v-spacer

		v-btn(flat href='/' target='_blank')
			span.mr-2

			v-icon all_inclusive

	v-content
		router-view
</template>

<script>

export default {
	name: 'App',
	data () {
		return {
		}
	}
}
</script>

<style lang="css">
		@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.9.0/css/all.min.css');
		@import url('https://fonts.googleapis.com/css?family=Material+Icons');
		@import url('https://fonts.googleapis.com/css?family=News+Cycle');

    body, html {
      font-family: 'News Cycle' ,sans-serif !important;
      height: 100%;
      font-weight: 300 !important;
    }

    h1, h2, h3, h4, h5, h6 {
      font-family: 'News Cycle' ,sans-serif;
      font-weight: 300 !important;
    }

    .dignity {
      font-family: "News Cycle", sans-serif;
      font-weight: 300 !important;
    }

    .navbar-brand, .nav-link {
      font-family: 'News Cycle', sans-serif;
      font-weight: 300 !important;
    }

    i, .material-icons, .fa, .fab, .far, .fas {
      vertical-align: middle;
    }

</style>
