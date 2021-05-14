## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/kaushalnavneet/coursera-js/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

| Credential Name          | Where is the secret used?                                                        | Rotation Frequency (in days) | How to get a new secret? |
| ------------------------ | -------------------------------------------------------------------------------- | ---------------------------- | ---------------------------------- |
| cloudant-iam-apikey      | otc-pagerduty-broker, otc-slack-broker, otc-toolint-broker, otc-saucelabs-broker | 90                           | Request to `Mike Melick/Joel Cayne` (Core team) for a new key |
| pagerduty-apikey         | otc-pagerduty-broker                                                             | 365                          | Request to `Corey Pickford` for a new key (an apikey of a functional user `idsb3t2@us.ibm.com`) |
| pagerduty-apikey-2       | otc-pagerduty-broker                                                             | 365                          | Request to `Corey Pickford` for a new key (an apikey of a functional user `idsb3t2@us.ibm.com`) |
| slack-bot-token          | otc-slack-broker                                                                 | 365                          | Request to `Corey Pickford` for a new token (an apikey of a functional user `idsb3t2@us.ibm.com`) |
| idsorg-session-secret    | otc-cf-broker                                                                    | 365                          | Request to `Padraic Edwards` (Setup team) for a new secret - (Issue reference)[https://github.ibm.com/org-ids/roadmap/issues/14391#issuecomment-25866513] |
| idsorg-test-tiam-secret  | otc-pagerduty-broker, otc-slack-broker                                           | 90                           | Request to `Christophe Elek` (Core team) for a new secret - (Issue reference)[https://github.ibm.com/org-ids/roadmap/issues/15210] | 
| cti-otc-api-secret       | otc-cti-broker                                                                   | 365                          | Run command `base64 </dev/urandom \| tr -d '/+' \| head -c 50` |
| encryption-key           | otc-pagerduty-broker, otc-toolint-broker, otc-cti-broker                         | 90                           | Run command ` base64 </dev/urandom \| tr -d '/+' \| head -c 32 ` |
| pagerduty-otc-api-secret | otc-pagerduty-broker                                                             | 365                          | Run command `base64 </dev/urandom \| tr -d '/+' \| head -c 50` |
| saucelabs-otc-api-secret | otc-saucelabs-broker                                                             | 365                          | Run command `base64 </dev/urandom \| tr -d '/+' \| head -c 50` |
| slack-otc-api-secret     | otc-slack-broker                                                                 | 365                          | Run command `base64 </dev/urandom \| tr -d '/+' \| head -c 50` |
| toolint-otc-api-secret   | otc-toolint-broker                                                               | 365                          | Run command `base64 </dev/urandom \| tr -d '/+' \| head -c 50` |

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kaushalnavneet/coursera-js/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
