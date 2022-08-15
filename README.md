```go
var whoAmI = map[string]any{
	// This section holds some personal informations about me.
	"Name":     "Mahdi Hasani",
	"Email":    "m2hdtl@gmail.com",
	"Location": "Tehran, Iran",
	"Birth":    "1998-08-23",

	// This section holds informaton about my career path.
	"Career": map[string]map[string]string{
		"Nov 2021 - Present": {
			"Company":  "SnappFood.ir",
			"Position": "Back-End Software Engineer",
		},
		"Jul 2020 - Nov 2021": {
			"Company":  "HiTrav.com",
			"Position": "Back-End Software Engineer",
		},
	},

	// This section holds a list of technologies that I've worked with.
	"Stack": map[string][]string{
		"Languages":         {"Go", "PHP", "Bash"},
		"Frameworks":        {"gin-gonic/gin", "gorilla/mux", "symfony/symfony", "laravel/laravel", "laravel/lumen"},
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
