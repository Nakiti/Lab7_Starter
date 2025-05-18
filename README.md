1) I would put it within a github action because it removes the dependency of requiring people to remember to manually run tests. Additionally, it makes sure that the testing environment is standardized.
2) No
3) Navigation mode analyzes a page immediately after it loads and doesn't have any javascript interactions, and its primarily used to gain insight about loading speeds and optimization. Snapshot provides a view of the DOM tree so it can be used to measure accessibility. 
4) 
   1) Add a meta tag with name="viewpoint"
   2) Serve images in next gen format
   3) Reduce unused javascript
   





