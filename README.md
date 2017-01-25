<img src=https://raw.githubusercontent.com/KodeKunstner/unnamed-solsort-com-app/master/icon.png width=96 height=96 align=right>

[![github](https://img.shields.io/badge/github-KodeKunstner/unnamed-solsort-com-app-blue.svg)](https://github.com/KodeKunstner/unnamed-solsort-com-app)
[![codeclimate](https://img.shields.io/codeclimate/github/KodeKunstner/unnamed-solsort-com-app.svg)](https://codeclimate.com/github/KodeKunstner/unnamed-solsort-com-app)

# Hello world, this is a test

This is a bit of documentation, try 'Read' above. Code can be written as semi-literate code, see more here <https://en.wikipedia.org/wiki/Literate_programming>
    
    module.meta = {
      name: 'Sample Application',
      version: '0.0.1'
    };
    var da = require('direape@0.1');
    da.run(da.parent, 'appedit:html',`
    <center>
      <h1>Change me</h1>
      <p>Try to edit the code.</p>
      <p>Choose Edit above, and then<br>
         alter the code on the left side...</p>
      (vi keybindings is enabled,<br>
      so press <tt>i</tt> to insert)
    </center>
    ${Object.keys(require('lodash')).join('<br>')}
    `);