# Atomic-Dark-LAF

-- not complete --

A simple dark look and feel for Java swing applications, using Synth XML.
Created by me because of my frustration with the lack of dark swing look and feels (or actually nice lafs)

Due to the use of symlinks, may not work correctly on Windows, but I don't really know. Does Windows do symlinks?

I'm finding java swing a bit convoluted, especially when it comes to styling it, especially with synth, so I'm considering just creating some of my own components as alternatives to swing ones, so this project may never be complete.

### Usage

Before initialising ui:

```java
SynthLookAndFeel laf = new SynthLookAndFeel();
try {
  laf.load(< load file however you want - example: Main.class.getResource("/AtomicDark.xml") >);
	UIManager.setLookAndFeel(laf);
} catch(ParseException | UnsupportedLookAndFeelException | IOException e) {
	e.printStackTrace();
}
```
