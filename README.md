```go
var whoAmI = map[string]any{
	// This section holds some personal informations about me.
	"Name":     "Mahdi Hasani",
	"Email":    "mahdi.hasani.eng@gmail.com",
	"Location": "Tehran, Iran",
	"Birth":    "1998-08-23",

	// This section holds informaton about my career path.
	"Career": map[string]map[string]string{
		"Jan 2023 - Present": {
			"Company":  "Sheypoor.ir",
			"Position": "Software Engineer",
		},
		"Nov 2021 - Jan 2023": {
			"Company":  "Snappfood.ir",
			"Position": "Software Engineer",
		},
		"Jul 2020 - Nov 2021": {
			"Company":  "HiTrav.com",
			"Position": "Software Engineer",
		},
	},

	// This section holds a list of technologies that I've worked with.
	"Stack": map[string][]string{
		"Languages":         {"Go", "Python", "PHP", "Bash"},
		"Frameworks":        {"gin-gonic/gin", "gorilla/mux", "symfony/symfony", "laravel/laravel"},
		"Databases":         {"MySQL", "CassandraDB"},
		"Caches":            {"Redis"},
		"Message Queues":    {"RabbitMQ"},
		"Operating Systems": {"Linux"},
		"Containerizations": {"Docker"},
		"Version Controlls": {"Git"},
		"Other Tools":       {"Jira"},
	},
}
```
