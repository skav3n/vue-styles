# vue-styles

### Create tag
```
git tag <tagname>
git push origin <tagname>
```

### Delete a local Git tag
```
git tag -d <tagname>
```

### Delete a remote Git tag
```
git push --delete origin <tagname>
```

### Full import Element Plus
```
@use '~vue-styles/index';
```

### Manually import Element Plus
```
@use '~vue-styles/styles/element-variables';
@use '~element-plus/theme-chalk/src/<element_component>';
@use '~vue-styles/styles/element-styles';
@use '~vue-styles/styles/core';
```
