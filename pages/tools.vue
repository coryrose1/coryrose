<template>
    <div class="mb-20 mt-10 items-baseline md:border-t md:border-gray-400 md:pt-2 lg:border-t-0 lg:pt-0">
        <div class="md:flex md:justify-between">
            <div class="md:w-1/4">
                <h2 class="font-medium sm:font-normal text-xl sm:text-2xl md:text-3xl lg:text-4xl text-gray-900">
                    Tools</h2>
            </div>
            <div class="md:w-3/4 mt-4 md:mt-0">
                <div class="text-lg sm:text-xl lg:text-2xl text-gray-700"><p>The list below details the
                    languages, tools, and various other things that I'm familiar with or use on a regular basis.</p>
                </div>
            </div>
        </div>
        <div class="py-6 sm:py-8 lg:py-10">
            <div class="mt-8 flex flex-wrap">
                <tool-list title="PHP">
                    <li class="font-semibold">Laravel</li>
                    <li>Symfony</li>
                    <li>CodeIgniter</li>
                </tool-list>
                <tool-list title="Javascript">
                    <li class="font-semibold">VueJS</li>
                    <li>Nuxt.js</li>
                    <li>React</li>
                    <li>jQuery</li>
                </tool-list>
                <tool-list title="CSS">
                    <li class="font-semibold">TailwindCSS</li>
                    <li>Bootstrap</li>
                    <li>Bulma</li>
                    <li>Foundation</li>
                </tool-list>
                <tool-list title="Various">
                    <li>Python</li>
                    <li>Git</li>
                    <li>MySQL</li>
                </tool-list>
                <tool-list title="Package Managers">
                    <li>Composer</li>
                    <li>NPM</li>
                    <li>Yarn</li>
                </tool-list>
                <tool-list title="IDEs/Editors">
                    <li>PHPStorm</li>
                    <li>Visual Studio</li>
                    <li>Sublime Text</li>
                </tool-list>
                <tool-list title="Site Builder/CMS">
                    <li>WordPress</li>
                    <li>SquareSpace</li>
                    <li>Wix</li>
                </tool-list>
                <tool-list title="Email">
                    <li>GSuite</li>
                    <li>Mailchimp</li>
                    <li>Mailgun</li>
                    <li>Sendgrid</li>
                    <li>Sparkpost</li>
                </tool-list>
            </div>
        </div>
    </div>
</template>

<script>
    import ToolList from "../components/ToolList";
    export default {
        name: "tools",
        components: {
            ToolList
        }
    }
</script>

<style scoped>

</style>