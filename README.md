# Limn Data &mdash; Example

[Limn][limn] is a GUI Visualization Toolkit.  This repository is an example of the data [Limn][limn] can currently understand and visualize.


## Using with Limn

 * Install [Limn][limn]

```
git clone git@github.com:wikimedia/limn.git
cd /path/to/limn
npm install
```

 * Link [Limn][limn] to [Limn Data][limn_data]

```
cd /path/not/under/limn
git clone git@github.com:wikimedia/limn-data.git
cd /path/to/limn
coke --vardir ./var --data /absolute/path/to/limn-data --to example link_data
npm start
```

 * IMPORTANT: use an absolute path as your --data parameter.  Relative paths are possible but harder to explain
 * Browse [A Sample Dashboard][sample_dashboard]

[limn_data]: https://github.com/wikimedia/limn-data "Limn Data on GitHub"
[limn]: https://github.com/wikimedia/limn "Limn on GitHub"
[sample_dashboard]: http://localhost:5000/dashboards/sample
