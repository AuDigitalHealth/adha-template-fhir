# Template inclusions
This FHIR template adds the following specific styling elements:

## 1. ./includes
### a) `/_append.fragment-css.html`
The FHIR-technology specific CSS is introduced (`content/assets/css/ADHA-fhir.css`)

See below for the specific styling localisations in `ADHA-fhir.css`.

## 2. ./layouts
No layout localisations have been introduced in this template

## 3. ./scripts
No scripts have been introduced in this template

## 4. CSS Styling
The CSS file `content/assets/css/ADHA-fhir.css` includes the following styling localisations:

### a) Resource canonical table
This is the table rendered at the top of the page for each resource, that includes official URL, status, version and copyright statement.

#### Background colour
* setting: `table.colsd td > background-color`
* set to what is found in HL7AU and international IGs: [`#ffffe6`](https://www.color-hex.com/color/ffffe6)

### b) XML snippet panes
This affects the rendering of resource example XML snippets.

#### Background colour
* setting: `:not(pre) > code[class*="language-xml"], pre[class*="language-xml"] background`
* set to replicate the background colour of StructureDefinition xml snippets [`#F0FFFF`](https://www.color-hex.com/color/F0FFFF)

#### Pane width
* setting: `pre.xml width`
* set to 100% to maximise the viewing area

#### pane content wrapping
This setting ensures that the content of example XML snippets wrap within the pane, rather than extend un-wrapped hidden and inaccessible to the right of the pane
* setting: `code[class*="language-xml"] white-space`
* set to `break-spaces`

### c) JSON snippet panes
This affects the rendering of resource example JSON snippets.

#### Background colour
* setting: `:not(pre) > code[class*="language-json"], pre[class*="language-json"] background`
* set to replicate the background colour of StructureDefinition json snippets [`#EFFFEF`](https://www.color-hex.com/color/EFFFEF)

#### Pane width
* setting: `pre.json width`
* set to 100% to maximise the viewing area

#### pane content wrapping
This setting ensures that the content of example JSON snippets wrap within the pane, rather than extend un-wrapped hidden and inaccessible to the right of the pane
* setting: `code[class*="language-json"] white-space`
* set to `break-spaces`

### d) RDF snippet panes
This affects the rendering of resource example RDF snippets.

#### Background colour
* setting: `:not(pre) > code[class*="language-rdf"], pre[class*="language-rdf"] background`
* set to replicate the background colour of StructureDefinition RDF snippets [`#EFFFEF`](https://www.color-hex.com/color/EFFFEF)

#### Pane width
* setting: `pre.rdf width`
* set to 100% to maximise the viewing area

#### pane content wrapping
This setting ensures that the content of example RDF snippets wrap within the pane, rather than extend un-wrapped hidden and inaccessible to the right of the pane
* setting: `code[class*="language-rdf"] white-space`
* set to `break-spaces`