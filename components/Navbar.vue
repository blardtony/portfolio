<template>
    <div>
        <b-navbar toggleable="md" type="dark" variant="dark">
            <b-navbar-brand href="#">Logo</b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse"  is-nav>
                <b-navbar-nav class="ml-auto">
                    <b-nav-item 
                        to="/"
                    >
                        Accueil
                    </b-nav-item>
                    <b-nav-item 
                        to="about"
                    >
                        À propos
                    </b-nav-item>
                    <b-nav-item 
                        to="skills"
                    >
                        Compétences
                    </b-nav-item>
                    <b-nav-item 
                        to="projects"
                    >
                        Mes projet
                    </b-nav-item>
                    <b-nav-item
                        to="contact"
                    >
                        Contact
                    </b-nav-item>
                    
                </b-navbar-nav>

                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                    <b-nav-item 
                        rel="noopener noreferrer"
                        target="_blank" 
                        href="https://www.linkedin.com/in/tony-blard-1483a1168"
                        class="h4 mb-0"
                    >   
                        <font-awesome-icon :icon="['fab', 'linkedin']"/>
                    </b-nav-item>
                    <b-nav-item 
                        class="h4 mb-0"
                        target="_blank" 
                        href="https://github.com/blardtony"
                        rel="noopener noreferrer"
                    >   
                        <font-awesome-icon :icon="['fab', 'github']"/>
                    </b-nav-item>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
