### backgroud
I want to use interactive matplotlib in j-n with `%matplotlib widget`
### bug
it keeps showing `Error Displaying Widget`
### effortless tries
update pkg jupyter/matplotlib/ipywidgets, uninstall and install ipywidgets(won't install to the newest version),searching config,
intall dependencies, change to backend nbagg(also does not work)

### success
**check newest version of ipywidgets on library website, then `pip install package_name==version_number`, FIX !!!**
### lesson
when some pkgs does not work, first update them manually!! The directive `--update` won't bring u to newest version.
