# Change Log

All notable changes to the "bngl-grammar-vscode" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

- 0.2.6
Currently we have ```.bngl``` run button, a ```.gdat/.cdat/.scan``` file plotting buttons as well as highlighting and various snippets. This version added ```.scan``` file plotting button and updated ```parameter_scan``` snippet.

- 0.2.8
Added plotly plotting to ```gdat/cdat/scan``` files

- 0.2.9
Major behavior changes, every click on the built-in plotting now pops open a new tab. Plots retain context (warning: memory intensive) and autosize depending on the window it's opened in. Added a refresh button to do the resizing after opening. Included jQuery. Working nonce for scripts. GML viewer still under development.

- 0.3.0
Plots appear in active window to give it more size. Plots now have some options on the left of the plot. Lasso selecting plots allow you to sub select time series, this is subject to heavy modification in the future. 

- 0.3.1
Quote protecting paths so paths that contain spaces will work. Added seconds to timestamps.

- 0.3.2
Plotly hovermode default changed to closest, legends are on by default if there's <= 5 series

- 0.3.3
Included net files to the list of file extensions this extension supports and added the syntax for it. Various small behavior changes, couple bug fixes and a couple snippet changes.