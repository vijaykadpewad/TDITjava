class JColoeChooser Demo
import java.awr.event.*;
import java.awt.*;
import.javax.swing.*;

public class JColorDemo extends JFrame
implements ActionListener
{
JButton b;
Container c;

JColorChooserDemo()
{
c = getContentPne();

b = new JButton("Color Chooser");
b.addActionListener(this);

c.add(b);
}

public void actionPerformed(ActionEvent e)
{
Color intialcolor=Color.Red;
Color color=JColorChooser.showDialog(this,
"Select a color",initialcolor);
c.setBackground(color);
}
public static void main(String[] args)
{
JColorChooserDemo jColorChooser = new
JColorChooserDemo();
jColorChooser.setSize(400,400);
jColorChooser.setVisible(true);

jColorChooser.setDefaultCloseOperation(EXIT_ON_CLOSE);
}
}