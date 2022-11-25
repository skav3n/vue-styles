# mph-helper

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
@use '~mph-helper/index';
```

### Manually import Element Plus
```
@use '~mph-helper/styles/element-variables';
@use '~element-plus/theme-chalk/src/<element_component>';
@use '~mph-helper/styles/element-styles';
@use '~mph-helper/styles/core';
```
