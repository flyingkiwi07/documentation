# this i my test website
## Welcome to GitHub Pages
### Creating an AP Transaction
```
mutation {
  createTran(
    input: {
      tran: {
        companyid: "d5807643-d708-4844-825b-226294de53XX"
        subsystemid: "6112ad25-b975-4888-abcd-3effc0809f6d"
        ledgerid: "3a8c82d7-d1e1-4a3c-aa69-c20b7c14a53c"
        trantypeid: "aa429136-73b7-40cd-9e25-dabace98a527"
        currencyid: "214577de-661e-4c60-8e72-d097ca613dba"
        termid: "be36165e-d065-40dc-94c2-7131f9294f33"
        taxid: "5fd1b428-bf54-4d58-a661-1aa2f7ce482c"
        transDate: "2018-10-30"
        amount: 200
        taxAmt: 0
        discAmt: 0
        reference: "9999-22121"
        description: "AP tran"
        entRoleList: [
          {
            entityid: "d5873e8a-a97d-4a0c-b535-b86522d0e9ee"
            roleid: "618fa3a4-d4cf-40d2-a5d2-cbad491a75b2"
          }
        ]
      }
    }
  ) {
    tran {
      transNo
      id
      documentNo
      transDate
    }
  }
}


```

You can use the [editor on GitHub](https://github.com/flyingkiwi07/documentation/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/flyingkiwi07/documentation/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
