# Atomic-Dark-LAF

A simple dark look and feel for Java swing applications, using Synth XML.
Created by me because of my frustration with the lack of dark swing look and feels (or actually nice lafs)

Due to the use of symlinks, may not work correctly on Windows, but I don't really know. Does Windows do symlinks?

### Usage

```java
SynthLookAndFeel laf = new SynthLookAndFeel();
try {
  laf.load(< load file however you want - example: Main.class.getResource("/AtomicDark.xml") >);
	UIManager.setLookAndFeel(laf);
} catch(ParseException | UnsupportedLookAndFeelException | IOException e) {
	e.printStackTrace();
}
```
