# Standard Default Paper Template

Paper template.

Contributors: ?

## Contributing/Style

Please feel free to modify. If possible using a merge/pull
request model to simplify analysis. 

To ease collaboration, I (ndd) have used the following
format for LaTeX because it is complex to read otherwise
[^style].

- Lines are hard wrapped at 60 characters
- Each paragraph begins with a commented and dashed line:
- Each sentence is in between two commented lines:
- Lines are indented a tabstop from the nearest section.

```tex
% --------------------
\section{My Section}
% --------------------

  % --------------------
  This is a sentence. 
  %
  This is sentence number two, that spans multiple lines,
  but I'm am fine switching to softwrap if that is easier.
  %
  This is the last line of the paragraph.
  
  % --------------------
  A second paragraph...
```

[^style]: I am fully able to change, but we should agree on
  one so we can synchronize our editor settings.
