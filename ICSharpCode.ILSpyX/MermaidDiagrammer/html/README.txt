To edit the HTML/JS/CSS for the HTML diagrammer, open this folder in Visual Studio Code.

In that environment you'll find tasks (see https://code.visualstudio.com/Docs/editor/tasks to run and configure)
that you can run to

1.  Generate a model.json using the current Debug build of ilspycmd.
    This is required to build a diagrammer for testing in development using task 3.
2.  Transpile the .less into .css that is tracked by source control and embedded into ILSpyX.
3.  Generate a diagrammer for testing in development from template.html and the model.json generated by task 1.
4.  Auto-rebuild the development diagrammer by running either task 2 or 3 when the corresponding source files change.