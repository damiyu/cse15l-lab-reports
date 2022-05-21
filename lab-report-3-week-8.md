# Lab Report #4 Weeks 7-8




### Repo Links

[Our Markdown Parser](https://github.com/thanhnhanlam/markdown-parser) : [My Copy](https://github.com/damiyu/ourrepo)

[Their Markdown Parser](https://github.com/NuojinliXu/markdown-parser) : [My Copy](https://github.com/damiyu/theirrepo)

### Our Repo Tests

**Snippet 1**
For snippet 1, the correct output for MarkdownParse should be `[google.com, google.com, ucsd.edu]`.

The test:
```
@Test
    public void snippetOneTest() throws IOException {
        Path fileName = Path.of("snippet1.md");
        String content = Files.readString(fileName);
        ArrayList<String> links = MarkdownParse.getLinks(content);

        ArrayList<String> expected = new ArrayList<String>();
        expected.add("`google.com");
        expected.add("google.com");
        expected.add("ucsd.edu");

        assertEquals(expected, links);
    }
```

**Snippet 2**
For snippet 2, the correct output for MarkdownParse should be `[a.com, a.com(()), example.com]`.

**Snippet 3**
For snippet 3, the correct output for MarkdownParse should be `[https://www.twitter.com, https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule, https://cse.ucsd.edu/]`.

### Their Repo Tests


