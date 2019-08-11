<template>
    <div class="mb-20 md:flex mt-10 lg:mt-6 items-baseline md:border-t md:border-gray-400 md:pt-2 lg:border-t-0 lg:pt-0">
        <div class="w-full md:w-1/4"><h2
                class="font-medium sm:font-normal text-xl sm:text-2xl md:text-3xl lg:text-4xl text-gray-900">
            Projects</h2></div>
        <div class="w-full md:w-3/4 mt-6">
            <div class="text-lg sm:text-xl lg:text-2xl text-gray-700"><p>Currently, the majority of my projects are private or internal systems for clients.</p>
                <p class="mt-6">Here are a few of my favorite projects that I've previously made:</p></div>
            <div class="mt-6 lg:mt-10 border-b border-gray-400">
                <div class="border-t border-gray-400 py-6 sm:py-8 lg:py-10">
                    <div class="lg:flex items-center justify-between">
                        <div>
                          <h3 class="text-gray-900 sm:text-lg lg:text-xl font-semibold">Expense Reporting Platform</h3>
                            <div class="text-gray-700 text-sm sm:text-base lg:text-lg mt-2 sm:mt-3 lg:mt-3">
                                <p>Built for and used by a mid-sized organization, this app is used to track employee spending and personal expenses.</p>
                                <p class="mt-4">Each period, corporate credit card charges are imported to the system and individual reports are created
                                    for each employee. Employees can then detail their business expenses by assigning a client, a category, and adding a description.</p>
                                <p class="mt-4">Employees may also submit personal expenses for the period, which can be reviewed and approved by a team leader.</p>
                                <p class="mt-4">This project provides administrators with a wealth of information and oversight to manage corporate spending.</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="border-t border-gray-400 py-6 sm:py-8 lg:py-10">
                    <div class="lg:flex items-center justify-between">
                        <div><h3 class="text-gray-900 sm:text-lg lg:text-xl font-semibold">
                            <a href="https://mycoinguru.com/" class="hover:underline">My Coin Guru</a></h3>
                            <div class="text-gray-700 text-sm sm:text-base lg:text-lg mt-2 sm:mt-3 lg:mt-3">
                                <p>Built during the height of the 2017 craze, My Coin Guru is a cryptocurrency portfolio dashboard.</p>
                                <p class="mt-4">This app was fun and challenging, marking my first time deep-dive into VueJS. It even had seamless importing
                                of your crypto trade history via read-only API access to Coinbase, Binance, and more - before mainstream applications such as Blockfolio and Delta.</p>
                            </div>
                        </div>
                        <div class="flex flex-wrap text-gray-900 text-sm sm:text-base lg:text-lg mt-2 sm:mt-3 lg:mt-0">
                            <div class="lg:ml-8"><a href="https://mycoinguru.com/"
                                                    class="flex items-center group hover:underline">
                                <div class="relative w-6 h-6">
                                    <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"
                                         class="absolute group-hover:opacity-0 w-6 h-6">
                                        <path d="M19.5 11V21.5H2.5V4.5H13" stroke="#1A202C"></path>
                                        <path d="M7.5 16.5L21.5 2.5" stroke="#1A202C" stroke-linecap="round"></path>
                                        <path d="M15 2.5H21.5V9" stroke="#1A202C"></path>
                                    </svg>
                                    <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"
                                         class="absolute opacity-0 group-hover:opacity-100 w-6 h-6">
                                        <path d="M7.5 16.5L21.5 2.5" stroke="#1A202C" stroke-linecap="round"></path>
                                        <path d="M6.43934 15.4393C5.85355 16.0251 5.85355 16.9749 6.43934 17.5607C7.02512 18.1464 7.97487 18.1464 8.56066 17.5607L20 6.12132V22H2V4H17.8787L6.43934 15.4393Z"
                                              fill="#1A202C"></path>
                                        <path d="M15 2.5H21.5V9" stroke="#1A202C"></path>
                                    </svg>
                                </div>
                                <div class="mt-px ml-2 lg:hidden">Check out this project</div>
                            </a></div>
                        </div>
                    </div>
                </div>
                <div class="border-t border-gray-400 py-6 sm:py-8 lg:py-10">
                    <div class="lg:flex items-center justify-between">
                        <div>
                            <h3 class="text-gray-900 sm:text-lg lg:text-xl font-semibold">
                                College Baseball Recruiting Preparation Platform
                            </h3>
                            <div class="text-gray-700 text-sm sm:text-base lg:text-lg mt-2 sm:mt-3 lg:mt-3">
                                <p>Created for an organization intended to help high school baseball players prepare for college baseball and recruiting.</p>
                                <p class="mt-4">This application involved a premium subscription membership (via Stripe) that offered up-to-date information on Division I, II, and III baseball colleges,
                                guides and content from industry professionals, and the ability to create a download Player Profile.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "projects"
    }
</script>

<style scoped>

</style>
