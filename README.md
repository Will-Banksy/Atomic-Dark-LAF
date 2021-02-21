# Atomic-Dark-LAF

-- incomplete, discontinued --

Discontinued cause now I use C++ and Qt

A simple dark look and feel for Java swing applications, using Synth XML.
Created by me because of my frustration with the lack of dark swing look and feels (or actually nice lafs)

I don't know if Windows does symlinks, I think it does, but if not then this won't work

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
