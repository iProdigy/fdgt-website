```java
import com.github.twitch4j.chat.*;

class Example {
	public static void main(String[] args) {
		TwitchChat chat = TwitchChatBuilder.builder()
			.withBaseUrl("wss://irc.fdgt.dev") // Requires Twitch4J version 1.0.1+
			.build();
	}
}
```
