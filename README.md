```kotlin
object MyData {
    const val FULL_NAME = "Christian soto hernandez"
    const val MAIN_ROLE = "Android Developer"
    const val EMAIL = "kristian@kristianconk.me"

    fun getExperience(): List<Experience> {
        return listOf(
            Experience("Android Developer Sr", "Ualá", "Diciembre 2021 - Mayo 2024"),
            Experience("Android Developer and Lead", "Banregio", "2018 - 2021"),
            Experience(
                "Software developer and tech lead",
                "Cion computación integral",
                " 2012 - 2018"
            )
        )
    }

    fun getLanguageLevel(lang: String): String {
        return when (lang) {
            "es" -> "Hablante nativo"
            "en" -> "Competencia básica profesional"
            else -> "Sin conocimientos"
        }
    }

    fun getTechnicalSkills(): List<String> {
        return listOf(
            "Kotlin",
            "Java",
            "Gradle",
            "Javascript",
            "Swift",
            "Clean Architecture",
            "Android Studio",
            "Jetpack Compose",
            "SQLite/Room",
            "Retrofit",
            "Dagger",
            "RxAndroid",
            "Firebase",
            "Google Maps",
            "Google Play Store",
            "CI/CD",
            "Unit Testing",
            "Encription and Biometrics",
            "JSON:API" 
        )
    }
}

data class Experience(
    val position: String,
    val company: String,
    val rageDate: String
)

```



## Resume

I'm a Software developer since 2012 specialized in android since 2018. Fan of new technologies and professional challenges.

### Some of the projects I have participated in

- [Uala app](https://play.google.com/store/apps/details?id=ar.com.bancar.uala) Develop and maintianance requeriments of Ualá mobile application, Implements best practices like Unit Testing, update dependencies, documentation, smart commits and naming conventions. Migrate complete flows to Jetpack Compose. Use of agile metology for organize all teal activities.
- [Banregio banca movil](https://play.google.com/store/apps/details?id=com.cloudsourceit.banregio&hl=es) [Hey Banco](https://play.google.com/store/apps/details?id=com.banregio.hey) Develop new requirements for Banregio main app. Add google maps, session time managment, enable biometric for login, add security layer for sensitive data in device, connect with RESTful services using MVP, MVVM and clean architecture, implement unit testing, pull-request review. Deploy to google play store and huawei app gallery. Organize my team and work using Scrum, JIRA, Bitbucket and Confluence.
- [Somos el cambio](https://play.google.com/store/apps/details?id=com.sec.somoselcambio) Connect to backend in drupal with elastic search plugin that responses JSON:API format

### Education

[Electronic engineering](https://cedulaprofesional.sep.gob.mx/cedula/indexAvanzada.action?idCedula=9027828&idProfesionista=9193432&token=0312163E28D3F249083D497DF3D2D52AAB300F6E) at [UAM Iztapalapa](http://www.iztapalapa.uam.mx/)
