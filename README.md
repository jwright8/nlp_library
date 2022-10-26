# nlp library

# To use your library from colab

```
#flush the old directory
!rm -r  'my_library'

my_github_name = 'jwright8'  #change to your github account name

clone_url = f'https://github.com/{my_github_name}/nlp_library.git'

#this adds the library to colab so you can now import it
!git clone $clone_url

import nlp_library.nlp_library as nlp
```

# Test the import

`nlp.hello()`
