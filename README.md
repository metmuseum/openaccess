The Metropolitan Museum of Art Open Access CSV
===================

The [Metropolitan Museum of Art](http://www.metmuseum.org) presents over 5,000 years of art from around the world for everyone to experience and enjoy. The Museum lives in three iconic sites in New York City—The Met Fifth Avenue, The Met Breuer, and The Met Cloisters. Millions of people also take part in The Met experience online.

Since it was founded in 1870, The Met has always aspired to be more than a treasury of rare and beautiful objects. Every day, art comes alive in the Museum's galleries and through its exhibitions and events, revealing both new ideas and unexpected connections across time and across cultures.

The Metropolitan Museum of Art provides select datasets of information on more than 470,000 artworks in its Collection for unrestricted commercial and noncommercial use. To the extent possible under law, The Metropolitan Museum of Art has waived all copyright and related or neighboring rights to this dataset using [Creative Commons Zero](https://creativecommons.org/publicdomain/zero/1.0/). This work is published from: The United States Of America. You can also find the text of the CC Zero deed in the file [LICENSE](https://github.com/metmuseum/openaccess/blob/master/LICENSE) in this repository. These select datasets are now available for use in any media without permission or fee; they also include identifying data for artworks under copyright. The datasets support the search, use, and interaction with the Museum’s collection. 

At this time, the datasets are available in CSV format, encoded in UTF-8. While UTF-8 is the standard for multilingual character encodings, it is not correctly interpreted by Excel on a Mac. Users of Excel on a Mac can convert the UTF-8 to UTF-16 so the file can be imported correctly.

## Additional usage guidelines
### Images not included
Images are not included and are not part of the dataset. Companion artworks listed in the dataset covered by the policy are identified in the [Collection section](http://www.metmuseum.org/art/collection) of the Museum’s website  with the Creative Commons Zero (CC0) icon. 

For more details on how to use images of artworks in The Metropolitan Museum of Art’s collection, please visit our [Open Access](http://www.metmuseum.org/about-the-met/policies-and-documents/image-resources) page.

### Documentation in progress
This data is provided “as is” and you use this data at your own risk. The Metropolitan Museum of Art makes no representations or warranties of any kind. Documentation of the Museum’s collection is an ongoing process and parts of the datasets are incomplete. 

We plan to update the datasets with new and revised information on a regular basis. You are advised to regularly update your copy of the datasets to ensure you are using the best available information.

### Pull requests
Because these datasets are generated from our internal database, we do *not* accept pull requests. If you have identified errors or have extra information to share, please email us at [openaccess@metmuseum.org](mailto:openaccess@metmuseum.org) and we will forward to the appropriate department for review.

### How to clone/download the data file

**Download**: In order to properly download the CSV file and not load the entire file in the browser, visit [this page](https://github.com/metmuseum/openaccess/blob/master/MetObjects.csv) and then right-click on "Download" (if you are using a computer with a trackpad, hold down <kbd>control</kbd> while clicking the link). You should then see a contextual menu where you can choose "Save Link As..."

**Clone**: Note that the CSV file is stored using Git's LFS (large-file storage) system. If you want to clone the repository, you need to run the following command on your console (Terminal on macOS / Git Bash on Windows):

```console
$ git lfs clone https://github.com/metmuseum/openaccess
```

### Attribution
Please consider attributing or citing The Metropolitan Museum of Art's CC0 select datasets, especially with respect to research or publication. Attribution supports efforts to release other datasets in the future. It also reduces the amount of "orphaned data," helping to retain source links.

### Do not misrepresent the dataset
Do not mislead others or misrepresent the datasets or their source. You must not use The Metropolitan Museum of Art’s trademarks or otherwise claim or imply that the Museum or any other third party endorses you or your use of the dataset.

Whenever you transform, translate or otherwise modify the dataset, you must make it clear that the resulting information has been modified. If you enrich or otherwise modify the dataset, consider publishing the derived dataset without reuse restrictions.

The writers of these guidelines thank the [The Museum of Modern Art](http://www.moma.org/), [Tate](http://www.tate.org.uk/), [Cooper-Hewitt](http://www.cooperhewitt.org/), and [Europeana](http://www.europeana.eu/).
