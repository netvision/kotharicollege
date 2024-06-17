<template>
    <AppHeader />
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mb-12">
        <h2 class="text-2xl font-bold border-b-2">Courses Offered</h2>
        <p class="text-lg text-justify">The College imparts instruction and prepares girls for: </p>
        <ul>
            <li><strong>Two Year Master's Degree in:</strong>
                <ol>
                    <li>Hindi</li>
                    <li>Economics</li>
                    <li>Political Science</li>
                    <li>Sanskrit</li>
                    <li>Geography</li>
                    <li>English</li>
                    <li>History</li>
                </ol>
            </li>
            <li><strong>Three Year Bachelor's Degree in the following subjects:</strong>
                <ul>
                    <li><strong>Compulsory Subjects:</strong>
                        <ol>
                            <li>General English</li>
                            <li>General Hindi</li>
                            <li>Elementary Computer Course</li>
                            <li>Environmental Studies</li>
                        </ol>
                    </li>
                    <li><strong>Optional Subjects (B.A.):</strong>
                        <ol>
                            <li>English/Hindi-Any one</li>
                            <li>History/Sociology - Any one</li>
                            <li>Economics/Home Science - Any one</li>
                            <li>Political Science</li>
                            <li>Geography</li>
                        </ol>
                    </li>
                    <li><strong>Optional Subjects (B.Com.):</strong>
                        <ol>
                            <li>ABST</li>
                            <li>EAFM</li>
                            <li>Business Adm.</li>
                        </ol>
                    </li>
                    <li class="list-none font-semibold">Note: A student has to opt these subjects (one each from one group). She will be allotted her subjects strictly according to merit, subject to the availability of seats. Merit will be determined on the basis of marks secured in aggregate in the Senior Secondary Examination.</li>
                </ul>
            </li>
        </ul>

    </div>
    <Footer />
</template>
<style scoped>
ul{
    @apply list-disc list-inside text-lg
}
ol{
    @apply list-decimal list-inside text-lg
}
li{
    @apply ml-4
}
li li{
    @apply italic
}
</style>