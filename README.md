To reproduce

```bash
git clone https://github.com/Guitaricet/sample_project
cd sample_project
pip install -e .
cd ~
python
```

```python
import sample_project
sample_project.data  # raises error
```

More context on [stackoverflow](https://stackoverflow.com/questions/65819504/module-sample-project-has-no-attribute-data)

### Disclaimer:

My question is not "How to import `sample_project.data`?".
My question is "Why `sample_project.data` does not work after `import sample_project`?".
