# About me
```java
public class Frost extends User {
    public Frost() {
        super("frost", "Scotland", "frost#0723", "Java");

        UserManager.addUser(this);
    }
}

public abstract class User {
    private final String username;
    private final String country;
    private final String discord;
    private final Set<String> languages = new HashSet<>();

    public User(final String username, final String country, final String discord, final String... languages) {
        this.username = username;
        this.country = country;
        this.discord = discord;
        this.languages.addAll(Arrays.asList(languages));
    }

    public String getUsername() {
        return this.username;
    }

    public String getCountry() {
        return this.country;
    }

    public String getDiscord() {
        return this.discord;
    }

    public Set<String> getLanguages() {
        return this.languages;
    }
}
```
<img width="50%" align="left" src="https://github-readme-stats.vercel.app/api?username=frosxt&count_private=true&include_all_commits=true&show_icons=true&theme=midnight-purple&icon_color=fff&hide_border=true">
