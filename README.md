# Stratos Ecosystem Projects 

To add a project to the Stratos Ecosystem, you need to:

1. Fork this repository.
2. Add your logo image in a web-safe format to the folder `data/img/<project_id>/`.
3. Add an entry to the [projects.json](projects.json) file as example below.
4. Create a PR 


Criteria:

- `id` number must the next available integer number.
- `<project_id>` can only be string name without any symbol. It will be used as the project page url on ecosystem page.
- Project website should include explanation of project.
- The project image specified at `imageUrl` should be small, square, but high resolution, ideally a vector/svg. 
  located at `data/img/<project_id>/<project_image_name.svg>`
- There must be 2-5 preview images in total, located at `data/img/<project_id>/previewImages/`  
- `metadata` field is optional. Current supported input are all included in the example below.
- For smart contract, it's nice to have a verified source code on block explorer.
- Project have to use Stratos Ecosystem components like Stratos Chain or Stratos Decentralized Storage
- Project should have clear signs of activity, either traffic on the network, activity on GitHub, or community buzz.

```json
{
    "id":  999, 
    "projectId": "<project_id>",
    "name": "<project_name>",
    "imageUrl": "<project_image_name.svg>",
    "overview": "<one_sentence_project_overview>",
    "description": "<detailed_project_description>",
    "website": "<project_website_url>",
    "previewImages": [
      "img1.png",
      "img2.png",
      "img3.png"
    ],
    "metadata": {
      "twitter": "<twitter_link>",
      "discord": "<discord_link>",
      "github": "<github_link>",
      "telegram": "<telegram_link>",
      "contract": "<smart_contract_address>",
      "docs": "<document_link>"
    }
  }


```




