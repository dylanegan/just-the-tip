## [Convert a GitHub Issue Into a Pull Request](http://opensoul.org/blog/archives/2012/11/09/convert-a-github-issue-into-a-pull-request/)

### Prerequisites 

* [GitHub](https://github.com), an open issue and a branch you want to attach as a pull request.
* [hub](https://github.com/defunkt/hub)

### Just The Tip

```
hub pull-request -i <issue number> -b dylanegan:master -h dylanegan:<your branch>
```
