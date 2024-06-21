```go
var whoAmI = map[string]any{
	// This section holds some personal informations about me.
	"Name":     "Mahdi Hasani",
	"Email":    "mahdi.hasani.eng@gmail.com",
	"Birth":    "1998-08-23",

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
