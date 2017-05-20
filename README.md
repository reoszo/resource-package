# resource-package
离线资源包

## 包依赖
```
    dependencies: [{
        package1name: version1,
        package2name: version2
    }]
```
## 独立包信息
```
    {
        group: '', // 包分组（可以用于多业务共用）
        name: '', // 包名称（和 group 组成唯一性）
        version: '', // 包版本
        url: '', // 包地址
        // force: boolean // 强制更新
        dependencies: { // 和独立的 denpendencies 信息的分歧
            name1: version1,
            name2: version2
        }
    }
```