<template>
  <div class="home">
      <h1 class="section step7">Spark</h1>
     <section class="section">
         <h2>Typography Scale</h2>
         <p class="lead">Generated scale for use in typographic settings.</p>
         <b>Root Em (rem):</b>
         <div style="
             width: 1rem;
             height: 1rem;
             background: gray;
             margin-bottom: 1rem;
         "></div>
         <b class="fluid-minFontSize">minFontSize: </b><br>
         <b class="fluid-referenceFontSize">referenceFontSize: </b><br>
         <b class="fluid-firstBreakingPoint">firstBreakingPoint: </b><br>
         <b class="fluid-referenceBreakingPoint">referenceBreakingPoint: </b><br>
         <b class="fluid-typographicScale">typographicScaleRatio: </b><br>

         <div
            class="section scrollable negative expand mt-1 scales"
            style="height: 80vh; border: solid 1px gray;"
         >
             <p class="step10">Typography</p>
             <p class="step9">Typography</p>
             <p class="step8">Typography</p>
             <p class="step7">Typography</p>
             <p class="step6">Typography</p>
             <p class="step5">Typography</p>
             <p class="step4">Typography</p>
             <p class="step3">Typography</p>
             <p class="step2">Typography</p>
             <p class="step1">Typography</p>
             <p class="step0">Typography</p>
             <p class="step-1">Typography</p>
             <p class="step-2">Typography</p>
             <p class="step-3">Typography</p>
             <p class="step-4">Typography</p>
             <p class="step-5">Typography</p>
         </div>
         <p>
             There are 20 steps larger than base font size, and 20 negative steps, smaller
             than base font size. This values are available as SCSS variables.
             There are prototype classes available, but in the range from step-5 to step10.
         </p>
         <code>.step10</code><br>
         <code>.step9</code><br>
         <code>.step8</code><br>
         <code>.step7</code><br>
         <code>.step6</code><br>
         <code>.step5</code><br>
         <code>.step4</code><br>
         <code>.step3</code><br>
         <code>.step2</code><br>
         <code>.step1</code><br>
         <code>.step0</code><br>
         <code>.step-1</code><br>
         <code>.step-2</code><br>
         <code>.step-3</code><br>
         <code>.step-4</code><br>
         <code>.step-5</code><br>
     </section>
     <section class="section">
         <h2>Typography</h2>
         <div id="top" class="page" role="document">
           <header role="banner">
             <h3>HTML5 Test Page</h3>
             <p class="lead">
                 This is a test page filled with common HTML elements to be used
                 to provide visual feedback whilst building CSS systems and
                 frameworks.</p>
           </header>
           <nav role="navigation">
             <ul class="grid">
               <li>
                 <a class="bold" href="#text">Text</a>
                 <ul class="vertical">
                     <li><a class="button" href="#text__helpers">Text Helpers</a></li>
                     <li><a class="button" href="#text__headings">Headings</a></li>
                     <li><a class="button" href="#text__paragraphs">Paragraphs</a></li>
                     <li><a class="button" href="#text__blockquotes">Blockquotes</a></li>
                     <li><a class="button" href="#text__lists">Lists</a></li>
                     <li><a class="button" href="#text__hr">Horizontal rules</a></li>
                     <li><a class="button" href="#text__tables">Tabular data</a></li>
                     <li><a class="button" href="#text__code">Code</a></li>
                     <li><a class="button" href="#text__inline">Inline elements</a></li>
                 </ul>
               </li>
               <li>
                 <a class="bold" href="#embedded">Embedded content</a>
                 <ul class="vertical">
                   <li><a class="button" href="#embedded__images">Images</a></li>
                   <li><a class="button" href="#embedded__audio">Audio</a></li>
                   <li><a class="button" href="#embedded__video">Video</a></li>
                   <li><a class="button" href="#embedded__canvas">Canvas</a></li>
                   <li><a class="button" href="#embedded__meter">Meter</a></li>
                   <li><a class="button" href="#embedded__progress">Progress</a></li>
                   <li><a class="button" href="#embedded__svg">Inline SVG</a></li>
                   <li><a class="button" href="#embedded__iframe">IFrames</a></li>
                 </ul>
               </li>
               <li>
                 <a class="bold" href="#forms">Form elements</a>
                 <ul class="vertical">
                   <li><a class="button" href="#forms__input">Input fields</a></li>
                   <li><a class="button" href="#forms__select">Select menus</a></li>
                   <li><a class="button" href="#forms__checkbox">Checkboxes</a></li>
                   <li><a class="button" href="#forms__radio">Radio buttons</a></li>
                   <li><a class="button" href="#forms__textareas">Textareas</a></li>
                   <li><a class="button" href="#forms__html5">HTML5 inputs</a></li>
                   <li><a class="button" href="#forms__action">Action buttons</a></li>
                 </ul>
               </li>
             </ul>
           </nav>
           <main role="main">
             <section id="text">
               <header><h1>Text</h1></header>
               <article id="text__helpers">
                 <header>
                   <h2>Text Helpers</h2>
                 </header>
                 <code>.txtl</code><br>
                 <p class="txtl">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.txtc</code><br>
                 <p class="txtc">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.txtr</code><br>
                 <p class="txtr">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.bold</code><br>
                 <p class="bold">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.italic</code><br>
                 <p class="italic">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.smallcaps</code><br>
                 <p class="smallcaps">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.uppercase</code><br>
                 <p class="uppercase">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.lowercase</code><br>
                 <p class="lowercase">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.text-justify-left</code><br>
                 <p class="text-justify-left ">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.text-justify-right</code><br>
                 <p class="text-justify-right">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.text-justify-center</code><br>
                 <p class="text-justify-center">
                     Lorem Ipsum is simply dummy text of the printing and
                     typesetting industry. Lorem Ipsum has been the
                     industry's standard dummy text ever since the 1500s,
                     when an unknown printer took a galley of type and
                     scrambled it to make a type specimen book.</p>
                 <br>
                 <code>.avoid-break</code><br>
                 <h3 class="avoid-break">Lorem-Ipsum-Dolor-Sit-Amet</h3>
                 <br>
                 <code>.word-break</code><br>
                 <h3 class="word-break">Lorem-Ipsum-Dolor-Sit-Amet</h3>
                 <br>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__headings">
                 <header>
                   <h2>Headings</h2>
                 </header>
                 <div>
                   <h1>Heading 1</h1>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>
                   <h2>Heading 2</h2>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <h3>Heading 3</h3>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <h4>Heading 4</h4>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <h5>Heading 5</h5>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <h6>Heading 6</h6>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <hr>

                   <div class="alpha">Alpha Heading</div>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <div class="beta">Beta Heading</div>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <div class="gamma">Gamma Heading</div>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <div class="delta">Delta Heading</div>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <div class="epsylon">Epsylon Heading</div>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <div class="zeta">Zeta Heading</div>
                   <p>
                       Lorem Ipsum is simply dummy text of the printing and
                       typesetting industry. Lorem Ipsum has been the
                       industry's standard dummy text ever since the 1500s,
                       when an unknown printer took a galley of type and
                       scrambled it to make a type specimen book.</p>

                   <hr>
                   <section>
                       <header>
                           <h1>Heading 1</h1>
                           <h2>Additional Heading 2</h2>
                       </header>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </section>
                   <section>
                       <header>
                           <h2>Heading 2</h2>
                           <h3>Additional Heading 3</h3>
                       </header>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </section>
                   <section>
                       <header>
                           <h3>Heading 3</h3>
                           <h4>Additional Heading 4</h4>
                       </header>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </section>
                   <section>
                       <header>
                           <h4>Heading 4</h4>
                           <h5>Additional Heading 5</h5>
                       </header>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </section>
                   <section>
                       <header>
                           <h5>Heading 5</h5>
                           <h6>Additional Heading 6</h6>
                       </header>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </section>
                   <hr>
                   <div>
                       <div class="alpha">Alpha Heading</div>
                       <div class="beta">Additional Beta Heading</div>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </div>
                   <div>
                       <div class="beta">Beta Heading</div>
                       <div class="gamma">Additional Gamma Heading</div>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </div>
                   <div>
                       <div class="gamma">Gamma Heading</div>
                       <div class="delta">Additional Delta Heading</div>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </div>
                   <div>
                       <div class="delta">Delta Heading</div>
                       <div class="epsylon">Additional Epsylon Heading</div>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </div>
                   <div>
                       <div class="epsylon">Epsylon Heading</div>
                       <div class="zeta">Additional Gamma Heading</div>
                       <p>
                           Lorem Ipsum is simply dummy text of the printing and
                           typesetting industry. Lorem Ipsum has been the
                           industry's standard dummy text ever since the 1500s,
                           when an unknown printer took a galley of type and
                           scrambled it to make a type specimen book.</p>
                   </div>
                 </div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__paragraphs">
                 <header><h2>Paragraphs</h2></header>
                 <div>
                     <p class="lead">
                         <code>.lead</code>
                         A paragraph (from the Greek paragraphos, “to write
                         beside” or “written beside”)
                         is a self-contained unit of a discourse in writing
                         dealing with a particular point or idea.
                         A paragraph consists of one or more sentences.
                         Though not required by the syntax of any language,
                         paragraphs are usually an expected part of formal
                         writing, used to organize longer prose.
                     </p>
                   <p>
                       A paragraph (from the Greek paragraphos, “to write
                       beside” or “written beside”)
                       is a self-contained unit of a discourse in writing
                       dealing with a particular point or idea.
                       A paragraph consists of one or more sentences.
                       Though not required by the syntax of any language,
                       paragraphs are usually an expected part of formal
                       writing, used to organize longer prose.
                   </p>
                   <p class="small">
                       <code>.small</code>
                       A paragraph (from the Greek paragraphos, “to write
                       beside” or “written beside”)
                       is a self-contained unit of a discourse in writing
                       dealing with a particular point or idea.
                       A paragraph consists of one or more sentences. Though
                       not required by the syntax of any language,
                       paragraphs are usually an expected part of formal
                       writing, used to organize longer prose.
                   </p>
                 </div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__blockquotes">
                 <header><h2>Blockquotes</h2></header>
                 <div>
                   <blockquote>
                     <p>A block quotation (also known as a long quotation
                         or extract) is a quotation in a written document,
                         that is set off from the main text as a paragraph,
                         or block of text.</p>
                     <p>It is typically distinguished visually using
                         indentation and a different typeface or smaller size
                         quotation. It may or may not include a citation,
                         usually placed at the bottom.</p>
                     <cite><a href="#!">Said no one, ever.</a></cite>
                   </blockquote>
                 </div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__lists">
                 <header><h2>Lists</h2></header>
                 <div class="grid">
                     <div>
                         <h3>Definition list</h3>
                         <dl>
                           <dt>Definition List Title</dt>
                           <dd>This is a definition list division.</dd>
                         </dl>
                     </div>
                     <div>
                         <h3>Ordered List</h3>
                         <ol>
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ol>
                     </div>
                     <div>
                         <h3>Unordered List</h3>
                         <ul>
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ul>
                     </div>
                     <div>
                         <h3>Unordered List </h3>
                         <code>.in</code>
                         <ul class="in">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ul>
                     </div>
                     <div>
                         <h3>Unordered List </h3>
                         <code>.out</code>
                         <ul class="out">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ul>
                     </div>
                     <div>
                         <h3>Unordered List </h3>
                         <code>.nostyle</code>
                         <ul class="nostyle">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ul>
                     </div>
                     <div>
                         <h3>Unordered List </h3>
                         <code>.square</code>
                         <ul class="square">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ul>
                     </div>
                     <div>
                         <h3>Unordered List </h3>
                         <code>.circle</code>
                         <ul class="circle">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ul>
                     </div>
                     <div>
                         <h3>Unordered List </h3>
                         <code>.disc</code>
                         <ul class="disc">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ul>
                     </div>
                     <div>
                         <h3>Ordered List</h3>
                         <code>.upperroman</code>
                         <ol class="upperroman">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ol>
                     </div>
                     <div>
                         <h3>Ordered List</h3>
                         <code>.lowroman</code>
                         <ol class="lowroman">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ol>
                     </div>
                     <div>
                         <h3>Ordered List</h3>
                         <code>.upperalpha</code>
                         <ol class="upperalpha">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ol>
                     </div>
                     <div>
                         <h3>Ordered List</h3>
                         <code>.lowalpha</code>
                         <ol class="lowalpha">
                           <li>List Item 1</li>
                           <li>List Item 2</li>
                           <li>List Item 3</li>
                         </ol>
                     </div>
                 </div>

                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__hr">
                 <header><h2>Horizontal rules</h2></header>
                 <div>
                   <hr>
                 </div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__tables">
                 <header><h2>Tabular data</h2></header>
                 <table>
                   <caption>Table Caption</caption>
                   <thead>
                     <tr>
                       <th>Table Heading 1</th>
                       <th>Table Heading 2</th>
                       <th>Table Heading 3</th>
                       <th>Table Heading 4</th>
                       <th>Table Heading 5</th>
                     </tr>
                   </thead>
                   <tfoot>
                     <tr>
                       <th>Table Footer 1</th>
                       <th>Table Footer 2</th>
                       <th>Table Footer 3</th>
                       <th>Table Footer 4</th>
                       <th>Table Footer 5</th>
                     </tr>
                   </tfoot>
                   <tbody>
                     <tr>
                       <td>Table Cell 1</td>
                       <td>Table Cell 2</td>
                       <td>Table Cell 3</td>
                       <td>Table Cell 4</td>
                       <td>Table Cell 5</td>
                     </tr>
                     <tr>
                       <td>Table Cell 1</td>
                       <td>Table Cell 2</td>
                       <td>Table Cell 3</td>
                       <td>Table Cell 4</td>
                       <td>Table Cell 5</td>
                     </tr>
                     <tr>
                       <td>Table Cell 1</td>
                       <td>Table Cell 2</td>
                       <td>Table Cell 3</td>
                       <td>Table Cell 4</td>
                       <td>Table Cell 5</td>
                     </tr>
                     <tr>
                       <td>Table Cell 1</td>
                       <td>Table Cell 2</td>
                       <td>Table Cell 3</td>
                       <td>Table Cell 4</td>
                       <td>Table Cell 5</td>
                     </tr>
                   </tbody>
                 </table>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__code">
                 <header><h2>Code</h2></header>
                 <div>
                   <p><strong>Keyboard input:</strong> <kbd>Cmd</kbd></p>
                   <p><strong>Inline code:</strong> <code>&lt;div&gt;code&lt;/div&gt;</code></p>
                   <p>
                       <strong>Sample output:</strong>
                       <samp>This is sample output from a computer program.</samp>
                   </p>
                   <h2>Pre-formatted text</h2>
                   <pre>P R E F O R M A T T E D T E X T
       ! " # $ % &amp; ' ( ) * + , - . /
       0 1 2 3 4 5 6 7 8 9 : ; &lt; = &gt; ?
       @ A B C D E F G H I J K L M N O
       P Q R S T U V W X Y Z [ \ ] ^ _
       ` a b c d e f g h i j k l m n o
       p q r s t u v w x y z { | } ~ </pre>
                 </div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="text__inline">
                 <header><h2>Inline elements</h2></header>
                 <div>
                   <p><a href="#!">This is a text link</a>.</p>
                   <p><strong>Strong is used to indicate strong importance.</strong></p>
                   <p><em>This text has added emphasis.</em></p>
                   <p>The <b>b element</b> is stylistically different text
                       from normal text, without any special importance.</p>
                   <p>The <i>i element</i> is text that is offset from the
                       normal text.</p>
                   <p>The <u>u element</u> is text with an unarticulated,
                       though explicitly rendered, non-textual annotation.</p>
                   <p><del>This text is deleted</del> and <ins>This text
                       is inserted</ins>.</p>
                   <p><s>This text has a strikethrough</s>.</p>
                   <p>Superscript<sup>®</sup>.</p>
                   <p>Subscript for things like H<sub>2</sub>O.</p>
                   <p><small>This small text is small for for fine print, etc.</small></p>
                   <p>Abbreviation: <abbr title="HyperText Markup Language">HTML</abbr></p>
                   <p><q cite="https://developer.mozilla.org/en-US/docs/HTML/Element/q">This text is a short inline quotation.</q></p>
                   <p><cite>This is a citation.</cite></p>
                   <p>The <dfn>dfn element</dfn> indicates a definition.</p>
                   <p>The <var>variable element</var>, such as <var>x</var> = <var>y</var>.</p>
                   <p>The time element:
                       <time datetime="2013-04-06T12:32+00:00">2 weeks ago</time>
                   </p>
                   <p>The <mark>mark element</mark> indicates a highlight.</p>
                   <p>
                       <mark class="feature">Mark featured <code>.feature</code> </mark><br>
                       <mark class="todo">Mark todo <code>.todo</code> </mark><br>
                       <mark class="review">Mark review <code>.review</code> </mark><br>
                       <mark class="issue">Mark issue <code>.issue</code> </mark><br>
                       <mark class="proposal">Mark proposal <code>.proposal</code> </mark><br>
                   </p>
                 </div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>

             </section>
             <section id="embedded">
               <header><h2>Embedded content</h2></header>
               <article id="embedded__images">
                 <header><h3>Images</h3></header>
                 <ul class="nostyle grid">
                     <li>
                         <h4>No <code>figure</code> element</h4>
                         <p><img src="http://placekitten.com/480/480" alt="Image alt text"></p>
                     </li>
                     <li>
                         <h4>No <code>figure</code> element</h4>
                         <p><img class="fill" src="http://placekitten.com/480/480" alt="Image alt text"></p>
                     </li>
                     <li>
                         <h4>No <code>figure</code> element</h4>
                         <p><img class="contain" src="http://placekitten.com/480/480" alt="Image alt text"></p>
                     </li>
                     <li>
                         <h4>No <code>figure</code> element</h4>
                         <p><img class="cover" src="http://placekitten.com/480/480" alt="Image alt text"></p>
                     </li>
                     <li>
                         <h4>No <code>figure</code> element</h4>
                         <p><img class="scale-down" src="http://placekitten.com/480/480" alt="Image alt text"></p>
                     </li>
                     <li>
                         <h4>Wrapped in a
                         <code>figure</code> element, no
                         <code>figcaption</code></h4>
                         <figure><img src="http://placekitten.com/420/420" alt="Image alt text"></figure>
                     </li>
                     <li>
                         <h4>Wrapped in a <code>figure</code> element,
                             with a <code>figcaption</code></h4>
                         <figure>
                             <img src="http://placekitten.com/420/420" alt="Image alt text">
                             <figcaption>Here is a caption for this image.</figcaption>
                         </figure>
                     </li>

                 </ul>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="embedded__audio">
                 <header><h3>Audio</h3></header>
                 <div><audio controls="">audio</audio></div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="embedded__video">
                 <header><h3>Video</h3></header>
                 <div><video controls="">video</video></div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="embedded__canvas">
                 <header><h3>Canvas</h3></header>
                 <div><canvas>canvas</canvas></div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="embedded__meter">
                 <header><h3>Meter</h3></header>
                 <div><meter value="2" min="0" max="10">2 out of 10</meter></div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="embedded__progress">
                 <header><h3>Progress</h3></header>
                 <div><progress>progress</progress></div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="embedded__svg">
                 <header><h3>Inline SVG</h3></header>
                 <!-- eslint-disable-next-line -->
                 <div><svg width="100px" height="100px"><circle cx="100" cy="100" r="100" fill="#1fa3ec"></circle></svg></div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
               <article id="embedded__iframe">
                 <header><h3>IFrame</h3></header>
                 <div><iframe src="http://www.htmlicloud.com/iframesample.html" height="500"></iframe></div>
                 <footer><p class="txtr"><a href="#top">[Top]</a></p></footer>
               </article>
             </section>
             <section id="forms">
               <header><h2>Form elements</h2></header>
               <form>
                 <fieldset id="forms__input">
                   <legend>Input fields</legend>
                   <p>
                     <label for="input__text">Text Input</label>
                     <input id="input__text" type="text" placeholder="Text Input">
                   </p>
                   <p>
                     <label for="input__password">Password</label>
                     <input id="input__password" type="password" placeholder="Type your Password">
                   </p>
                   <p>
                     <label for="input__webaddress">Web Address</label>
                     <input id="input__webaddress" type="url" placeholder="http://yoursite.com">
                   </p>
                   <p>
                     <label for="input__emailaddress">Email Address</label>
                     <input id="input__emailaddress" type="email" placeholder="name@email.com">
                   </p>
                   <p>
                     <label for="input__phone">Phone Number</label>
                     <input id="input__phone" type="tel" placeholder="(999) 999-9999">
                   </p>
                   <p>
                     <label for="input__search">Search</label>
                     <input id="input__search" type="search" placeholder="Enter Search Term">
                   </p>
                   <p>
                     <label for="input__text2">Number Input</label>
                     <input id="input__text2" type="number" placeholder="Enter a Number">
                   </p>
                   <p>
                     <label for="input__text3" class="error">Error</label>
                     <input id="input__text3" class="is-error" type="text" placeholder="Text Input">
                     <code>.is-error</code>
                   </p>
                   <p>
                     <label for="input__text4" class="valid">Valid</label>
                     <input id="input__text4" class="is-valid" type="text" placeholder="Text Input">
                     <code>.is-valid</code>
                   </p>
                 </fieldset>
                 <p class="txtr"><a href="#top">[Top]</a></p>
                 <fieldset id="forms__select">
                   <legend>Select menus</legend>
                   <p>
                     <label for="select">Select</label>
                     <select id="select">
                       <optgroup label="Option Group">
                         <option>Option One</option>
                         <option>Option Two</option>
                         <option>Option Three</option>
                       </optgroup>
                     </select>
                   </p>
                 </fieldset>
                 <p class="txtr"><a href="#top">[Top]</a></p>
                 <fieldset id="forms__checkbox">
                   <legend>Checkboxes</legend>

                   <input type="checkbox" id="test1" />
                   <label for="test1">Red</label>

                   <ul class="nostyle">
                     <li><label for="checkbox1">
                         <input id="checkbox1" name="checkbox"
                         type="checkbox" checked="checked">
                         Choice A</label></li>
                     <li><label for="checkbox2">
                         <input id="checkbox2" name="checkbox"
                         type="checkbox">
                         Choice B</label></li>
                     <li><label for="checkbox3">
                         <input id="checkbox3" name="checkbox"
                         type="checkbox">
                         Choice C</label></li>
                   </ul>
                   <!--  -->
                   <!--  -->
                   <!--  -->
                   <!--  -->
                   <!--  -->
                   <!--  -->
                   <h3>TESTS INTEGRATION</h3>
                   <div class="checkbox">
                       <input id="check1" type="checkbox" name="check" value="check1">
                       <label for="check1">Checkbox No. 1</label>
                       <br>
                       <input id="check2" type="checkbox" name="check" value="check2">
                       <label for="check2">Checkbox No. 2</label>
                    </div>
                 </fieldset>
                 <!--  -->
                 <!--  -->
                 <!--  -->
                 <!--  -->
                 <!--  -->
                 <!--  -->
                 <!--  -->
                 <p class="txtr"><a href="#top">[Top]</a></p>
                 <fieldset id="forms__radio">
                   <legend>Radio buttons</legend>
                   <ul class="nostyle">
                     <li><label for="radio1">
                         <input id="radio1" name="radio"
                         type="radio" class="radio" checked="checked">
                         Option 1</label></li>
                     <li><label for="radio2">
                         <input id="radio2" name="radio"
                         type="radio" class="radio">
                         Option 2</label></li>
                     <li><label for="radio3">
                         <input id="radio3" name="radio"
                         type="radio" class="radio">
                         Option 3</label></li>
                   </ul>
                 </fieldset>
                 <p class="txtr"><a href="#top">[Top]</a></p>
                 <fieldset id="forms__textareas">
                   <legend>Textareas</legend>
                   TODO
                   <!-- <p>
                     <label for="textarea">Textarea</label>
                     <textarea
                        id="textarea" rows="8"
                        placeholder="Enter your message here"></textarea>
                   </p> -->
                 </fieldset>
                 <p class="txtr"><a href="#top">[Top]</a></p>
                 <fieldset id="forms__html5">
                   <legend>HTML5 inputs</legend>
                   <p>
                     <label for="ic">Color input</label>
                     <input type="color" id="ic" value="#000000">
                   </p>
                   <p>
                     <label for="in">Number input</label>
                     <input type="number" id="in" min="0" max="10" value="5">
                   </p>
                   <p>
                     <label for="ir">Range input</label>
                     <input type="range" id="ir" value="10">
                   </p>
                   <p>
                     <label for="idd">Date input</label>
                     <input type="date" id="idd" value="1970-01-01">
                   </p>
                   <p>
                     <label for="idm">Month input</label>
                     <input type="month" id="idm" value="1970-01">
                   </p>
                   <p>
                     <label for="idw">Week input</label>
                     <input type="week" id="idw" value="1970-W01">
                   </p>
                   <p>
                     <label for="idtl">Datetime-local input</label>
                     <input type="datetime-local" id="idtl" value="1970-01-01T00:00">
                   </p>
                 </fieldset>
                 <p class="txtr"><a href="#top">[Top]</a></p>
                 <fieldset id="forms__action">
                   <legend>Action buttons</legend>
                   <p>
                     <input type="submit" value="input type=submit">
                     <input type="button" value="input type=button">
                     <input type="reset" value="input type=reset">
                     <input type="submit" value="input disabled" disabled>
                   </p>
                   <p>
                     <button type="submit">&lt;button type=submit&gt;</button>
                     <button type="button">&lt;button type=button&gt;</button>
                     <button type="reset">&lt;button type=reset&gt;</button>
                     <button type="button" disabled>&lt;button disabled&gt;</button>
                   </p>
                 </fieldset>
                 <p class="txtr"><a href="#top">[Top]</a></p>
               </form>
             </section>
           </main>
         </div>
     </section>
     <section class="section">
         <h2>Prototyping Helpers</h2>
         <p class="lead">
             Classes made for structured manipulation of elements on the webpage.
         </p>
         <h3>Flex</h3>
         <code>.flex</code><br>
         <code>.col</code><br>
         <code>.col.cv</code><br>
         <code>.col.ch</code><br>
         <code>.row</code><br>
         <code>.row.cv</code><br>
         <code>.row.ch</code><br>
         <code>.row-wrap</code><br>
         <code>.grow</code><br>
         <code>.shrink</code><br>
         <code>.grow-0</code><br>
         <code>.grow-1</code><br>
         <code>.justify--start</code><br>
         <code>.justify--end</code><br>
         <code>.justify--center</code><br>
         <code>.justify--around</code><br>
         <code>.justify--between</code><br>

         <h3>Grid</h3>
         <code>.grid</code><br>
         <code>.grid-stretch</code><br>
         <code>.grid--liners</code><br>
         <code>.grid--teasers</code><br>
         <code>.grid--previews</code><br>

         <h3>Padding</h3>
         <code>.pt-0</code><br>
         <code>.pt-1</code><br>
         <code>.pt-2</code><br>
         <code>.pt-3</code><br>
         <code>.pt-4</code><br>
         <code>.pt-5</code><br>
         <code>.pb-0</code><br>
         <code>.pb-1</code><br>
         <code>.pb-2</code><br>
         <code>.pb-3</code><br>
         <code>.pb-4</code><br>
         <code>.pb-5</code><br>
         <code>.pl</code><br>
         <code>.pr</code><br>
         <code>.plr</code><br>

         <h3>Margin</h3>
         <code>.ma</code><br>
         <code>.mt-0</code><br>
         <code>.mt-1</code><br>
         <code>.mt-2</code><br>
         <code>.mt-3</code><br>
         <code>.mt-4</code><br>
         <code>.mt-5</code><br>
         <code>.mb-0</code><br>
         <code>.mb-1</code><br>
         <code>.mb-2</code><br>
         <code>.mb-3</code><br>
         <code>.mb-4</code><br>
         <code>.mb-5</code><br>

         <h3>Layout</h3>
         <code>.section</code><br>
         <code>.hide</code><br>
         <code>.crop</code><br>
         <code>.padd</code><br>
         <code>.expand</code><br>
     </section>
     <section class="section">
         <h2>Navigations</h2>
         <p class="lead">Every <code> nav > ul </code> context has a specific behaviour</p>
         <code>nav ul li a</code>
         <nav>
             <ul>
                 <li> <a href="#">Some Link</a> </li>
                 <li> <a href="#">Some Link</a> </li>
                 <li> <a href="#">Some Link</a> </li>
             </ul>
         </nav>
         <code>nav ul li a.button</code>
         <nav>
             <ul>
                 <li> <a class="button" href="#">Some Link</a> </li>
                 <li> <a class="button" href="#">Some Link</a> </li>
                 <li> <a class="button" href="#">Some Link</a> </li>
             </ul>
         </nav>
         <code>nav ul.vertical li a</code>
         <nav>
             <ul class="vertical">
                 <li> <a href="#">Some Link</a> </li>
                 <li> <a href="#">Some Link</a> </li>
                 <li> <a href="#">Some Link</a> </li>
             </ul>
         </nav>
         <code>nav ul.vertical li a.button</code>
         <nav>
             <ul class="vertical">
                 <li> <a class="button" href="#">Some Link</a> </li>
                 <li> <a class="button" href="#">Some Link</a> </li>
                 <li> <a class="button" href="#">Some Link</a> </li>
             </ul>
         </nav>
     </section>
     <section class="section column-baseline-grid crop">
         <h2>Column Baseline Grid</h2>
         <p class="lead">
             Helper that is configurable.
             Easy way to maintain vertical rhytm, and horizontal grid.
         </p>
         <code>.column-baseline-grid</code><br>
         <p>Some text</p>
     </section>
     <section class="section">
         <h2>Collection Helpers</h2>
         <p class="lead">
             Default collection and items classes.
             Made for prototyping purpose, to have
             quick way of setting up layout.
         </p>
         <code>.collection</code><br>
         <code>.collection-item</code><br>
         <code>.view</code><br>
         <code>.preview</code><br>
         <code>.teaser</code><br>
         <code>.liner</code><br>
     </section>
     <section class="section">
         <h2>Scrollable</h2>
         <p class="lead">
             Any container can have class scrollable,
             its purpose is to style scrollbars. It is CSS only solution.
         </p>
         <code>.scrollable</code><br>
         <div class="scrollable" style="height: 100px;">
             Lorem Ipsum is simply dummy text of the printing and typesetting industry.
             Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
             when an unknown printer took a galley of type and scrambled it to make

             a type specimen book.
             It has survived not only five centuries, but also the leap into electronic typesetting,
             remaining essentially unchanged. It was popularised in the 1960s with the release of
             Letraset sheets containing Lorem Ipsum passages, and more recently
             with desktop publishing
             software like Aldus PageMaker including versions of Lorem Ipsum.
         </div>
     </section>
     <section class="section">
         <h2>Schema Helper</h2>
         <p class="lead">
             Helper prototyped to improve Momentum visual helpers. Work in progress.
         </p>

         <div itemscope itemtype="https://schema.org/Person">
           <span itemprop="name">Jane Doe</span>
           <img src="https://media11.s-nbcnews.com/i/MSNBC/Components/Video/201911/f_mo_la_janedoe15_191118.jpg" itemprop="image" alt="Photo of Jane Doe"/>
           <span itemprop="jobTitle">Professor</span>
           <div itemprop="address" itemscope itemtype="https://schema.org/PostalAddress">
             <span itemprop="streetAddress">
               20341 Whitworth Institute
               405 N. Whitworth
             </span>
             <span itemprop="addressLocality">Seattle</span>,
             <span itemprop="addressRegion">WA</span>
             <span itemprop="postalCode">98052</span>
           </div>
           <span itemprop="telephone">(425) 123-4567</span>
           <a href="mailto:jane-doe@xyz.edu" itemprop="email">
             jane-doe@xyz.edu</a>
           Jane's home page:
           <a href="http://www.janedoe.com" itemprop="url">janedoe.com</a>
           Graduate students:
           <a href="http://www.xyz.edu/students/alicejones.html" itemprop="colleague">
             Alice Jones</a>
           <a href="http://www.xyz.edu/students/bobsmith.html" itemprop="colleague">
             Bob Smith</a>
         </div>
     </section>
     <section class="section">
         <h2>Dims</h2>
         <p class="lead">
             Curently there is only one helper related to dims.
             It ads top margin to the website in order to make place for dims toolbar.
             Some editing helpers should be developed.
         </p>
     </section>
  </div>
</template>
<style lang="scss">
.scales {
    white-space: nowrap;
}
</style>
<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld,
  },
};
</script>
