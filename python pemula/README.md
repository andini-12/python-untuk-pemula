git add .
git status --short
$body = @'
Add two example scripts covering pip and virtual environments:
- pip_install.py: use a package installed with pip (colorama)
- 09-venv_check.py: show the Python executable and the active
  virtual environment path

Add screenshots of the tutorial page, pip list, and the output of
each script.
'@
git commit -m "feat(python-basics): add pip and virtual environment examples with screenshots" -m $body
git push origin main