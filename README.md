# WindowTemplatesUnity
Simple to use templates for creating templates in unity

#Installing
Simply drag the templates into:

*\Unity\Editor\Data\Resources\ScriptTemplates

# Using

After installation there will be and option for EditorWindow in left mouse click creation in Unity's assets folder

First Create an Editor Window Attribute
Second Create an Editor Window

BOTH WITH SAME NAME

Now on Unity you can select your window on the Window tab, and inspect elements there are tagged with [YOUR_WINDOW_NAME]

# Custom Inspectors

Simply insert a function called "void On'YOUR_WINDOW_NAME'GUI ()" and it edit it just like you do on OnInspectorGUI()