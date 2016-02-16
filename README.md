#Debugger

#ScreenShot

![Debugger](Debugger.png)

#Code

~~~
package ph.edu.dlsu;

import java.net.URI;
import java.net.URISyntaxException;

public class Main {

    public static void main(String[] args) {

        try {
            URI uri = new URI("http://dlsu.edu.ph");
        } catch (URISyntaxException e) {
            System.out.println(e.getMessage());
        }

        System.out.println("It's running!");

    }
}
~~~
