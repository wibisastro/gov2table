# Welcome to the gov2table wiki!
## Tag
```
<gov2table
        :get-url=""
        :columns="">
</gov2table>
```
## Property
- getUrl: type String **
- postUrl: type String **
- tagUrl: type String **
- tagsUrl: type Array **
- columns: type Array **
- filterKey: type String **
- readonly: type Boolean **
- recursive: type Boolean **
- itemPerPage: type Number **
- instance: {
        type: String,
        default: ""
    },
- childComponent: type Object **
- selected: type Number **
- tagCloseable: type Boolean **
- showTaggingAtLevel: type Number **
- tagLimit: type Number **
- taggingId: type Number **
- dynColName: {} **
- linkOn: {} **

## Data
 - isPressed: false
 ## Methods
 - toggleClick ** fungsinya mengubah nilai var isPresed ke nilai selain yang sedang terkandung
 - resetButton ** fungsinya mengubah nilai var isPresed ke false
 ## Created
 - resetButton ** listen event dengan value resetButton, jika ada eksekusi method resetButton di atas
