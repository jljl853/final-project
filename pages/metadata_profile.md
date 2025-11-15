---
title: Metadata Profile for Children Book Collection (1800–1980)
layout: about
permalink: /metadata_profile.html
credits: true
---


{% include feature/jumbotron.html heading="About: Metadata Application Profile" text="Descriptive metadata guidelines for the Children Book Collection (1800–1980)" objectid="cb-014" %} 

<div>
<h1>Metadata Application Profile for <cite>Children Book Collection (1800–1980)</cite></h1>

<div class="table-responsive">
<table class="table table-sm table-striped">

<thead>
<tr>
	<th><strong>Element Name</strong></th>
	<th><strong>Dublin Core Mapping</strong></th>
	<th><strong>Value Scheme</strong></th>
	<th><strong>Obligation</strong></th>
	<th><strong>Occurrence</strong></th>
	<th><strong>Input Guidelines</strong></th>
	<th><strong>Examples</strong></th>
</tr>
</thead>

<tbody>

<tr>
	<td>objectid</td>
	<td>Identifier</td>
	<td></td>
	<td>M</td>
	<td>NR</td>
	<td>objectid should be in the form <code>cb-NNN</code>, where NNN is a three-digit, zero-padded number assigned sequentially (e.g., 000, 001, 002).</td>
	<td>
		<ul>
			<li><code>cb-000</code></li>
			<li><code>cb-001</code></li>
			<li><code>cb-002</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>filename</td>
	<td>Identifier</td>
	<td></td>
	<td>M</td>
	<td>NR</td>
	<td>Enter the exact file name of the primary digital object located in <code>/objects/</code>. Must match the uploaded file name, including extension.</td>
	<td>
		<ul>
			<li><code>Secret-garden.pdf</code></li>
			<li><code>Cinderella-1870.jpg</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>title</td>
	<td>Title</td>
	<td></td>
	<td>M</td>
	<td>R</td>
	<td>Transcribe the chief title exactly as it appears on the title page, preserving original spelling and punctuation.</td>
	<td>
		<ul>
			<li><code>The Secret Garden</code></li>
			<li><code>Cinderella</code></li>
			<li><code>Beauty and the Beast</code></li>
			<li><code>London Town</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>format</td>
	<td>Format</td>
	<td><a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/IMT/">IMT (IANA Media Types)</a></td>
	<td>M</td>
	<td>NR</td>
	<td>Enter the MIME type of the digital file.</td>
	<td>
		<ul>
			<li><code>image/jpeg</code></li>
			<li><code>application/pdf</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>latitude</td>
	<td>Spatial</td>
	<td></td>
	<td>Opt</td>
	<td>NR</td>
	<td>Enter decimal latitude for place of publication (when known). Use standard decimal notation. Optional, but supports map visualization.</td>
	<td>
		<ul>
			<li><code>51.5072</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>longitude</td>
	<td>Spatial</td>
	<td></td>
	<td>Opt</td>
	<td>NR</td>
	<td>Enter decimal longitude for place of publication (when known). Use standard decimal notation. Optional, but supports map visualization.</td>
	<td>
		<ul>
			<li><code>-0.1276</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>subject</td>
	<td>Subject</td>
	<td><a href="https://www.loc.gov/aba/publications/FreeLCSH/freelcsh.html">LCSH</a></td>
	<td>Rec</td>
	<td>R</td>
	<td>Assign topical subjects using authorized Library of Congress Subject Headings (LCSH). Separate multiple terms with semicolons. A controlled vocabulary list should be maintained.</td>
	<td>
		<ul>
			<li><code>Orphans—Fiction; Gardens—Fiction; Yorkshire (England)—Juvenile fiction</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>date</td>
	<td>Date</td>
	<td><a href="https://www.w3.org/TR/NOTE-datetime">W3CDTF</a></td>
	<td>M</td>
	<td>NR</td>
	<td>Record publication date in W3CDTF format. Use <code>YYYY</code> or <code>YYYY-MM-DD</code> when full date is available. Required for timeline visualization.</td>
	<td>
		<ul>
			<li><code>1911</code></li>
			<li><code>1860-06-14</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>location</td>
	<td>Location</td>
	<td><a href="https://www.getty.edu/research/tools/vocabularies/tgn/">Getty TGN</a></td>
	<td>Rec</td>
	<td>NR</td>
	<td>Record city and country of publication, or city and state, separated by a comma. Use authorized form from Getty Thesaurus of Geographic Names (TGN) or related controlled vocabularies.</td>
	<td>
		<ul>
			<li><code>London</code></li>
			<li><code>New York</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>creator / author</td>
	<td>Creator</td>
	<td><a href="https://id.loc.gov/authorities/names.html">LCNAF</a></td>
	<td>M</td>
	<td>R</td>
	<td>Record author’s name in authorized form: Surname, Forename. Use LC Name Authority File (LCNAF). Repeat for multiple authors and separate by semicolons.</td>
	<td>
		<ul>
			<li><code>Burnett, Frances Hodgson</code></li>
			<li><code>Leigh, Felix; Crane, Thomas</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>illustrator</td>
	<td>Creator</td>
	<td><a href="https://id.loc.gov/authorities/names.html">LCNAF</a></td>
	<td>RA</td>
	<td>R</td>
	<td>Record illustrator’s name in authorized form: Surname, Forename. Use LCNAF. Repeat and separate multiple names with semicolons. Used to distinguish illustrators from authors and translators.</td>
	<td>
		<ul>
			<li><code>Houghton, Ellen Elizabeth</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>translator</td>
	<td>Creator</td>
	<td><a href="https://id.loc.gov/authorities/names.html">LCNAF</a></td>
	<td>RA</td>
	<td>R</td>
	<td>Record translator’s name in authorized form: Surname, Forename. Use LCNAF. Repeat and separate multiple names with semicolons. Leave blank if no translator is identified.</td>
	<td>
		<ul>
			<li><code>Hanna, Mohammad</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>publisher</td>
	<td>Publisher</td>
	<td><a href="https://id.loc.gov/authorities/names.html">LCNAF</a></td>
	<td>Rec</td>
	<td>NR</td>
	<td>Record publisher’s name in authorized form. Use LCNAF format; if multiple publishers are given, separate with semicolons. Leave blank if unknown.</td>
	<td>
		<ul>
			<li><code>Marcus Ward.</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>description</td>
	<td>Description</td>
	<td></td>
	<td>Rec</td>
	<td>NR</td>
	<td>Describe the book and provide a 1–3 sentence abstract summarizing the plot, themes, and visual style.</td>
	<td>
		<ul>
			<li><code>A novel about an orphaned girl who discovers a locked garden.</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>source</td>
	<td>Source</td>
	<td></td>
	<td>RA</td>
	<td>NR</td>
	<td>Enter the name of the website, institution, archive, or collection that holds or digitized the book.</td>
	<td>
		<ul>
			<li><code>Juvenile Collection (Library of Congress)</code></li>
			<li><code>Children’s Literature and Culture (Adam Matthew Digital)</code></li>
			<li><code>Internet Archive Digital Library</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>image_source</td>
	<td></td>
	<td></td>
	<td>Rec</td>
	<td>NR</td>
	<td>Enter the name of the institution, website, or repository that provided the image of the cover page or illustration.</td>
	<td>
		<ul>
			<li><code>Library of Congress</code></li>
			<li><code>Internet Archive</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>image_source_link</td>
	<td></td>
	<td>URL</td>
	<td>Rec</td>
	<td>NR</td>
	<td>Enter the direct, persistent link (URL) to the image or item page on the source platform. Must begin with <code>http</code> or <code>https</code>.</td>
	<td>
		<ul>
			<li><code>https://www.loc.gov/resource/rbc0001.2006gen32405/?sp=1&amp;r=-0.784,-0.027,2.567,1.378,0</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>type</td>
	<td>Type</td>
	<td><a href="https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/">DCMI Type Vocabulary</a></td>
	<td>RA</td>
	<td>NR</td>
	<td>Select from DCMI Type Vocabulary. For PDFs, use <code>Text</code>; for images, use <code>Image; StillImage</code>.</td>
	<td>
		<ul>
			<li><code>Text</code></li>
			<li><code>Image; StillImage</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>identifier</td>
	<td>Identifier</td>
	<td></td>
	<td>Rec</td>
	<td>NR</td>
	<td>Enter the unique identifier assigned by the source institution or repository (e.g., call number, catalog record number, or digital ID). Use the identifier exactly as shown in the source record. Leave blank if none exists.</td>
	<td>
		<ul>
			<li><code>PZ7.B934 Se 1911</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>genre</td>
	<td>Subject</td>
	<td><a href="https://id.loc.gov/authorities/genreForms.html">LCGFT</a></td>
	<td>Rec</td>
	<td>R</td>
	<td>Enter the genre or literary form of the item using controlled vocabulary from Library of Congress Genre/Form Terms (LCGFT). A controlled vocabulary list should be maintained.</td>
	<td>
		<ul>
			<li><code>Fairy tales</code></li>
			<li><code>Picture books</code></li>
			<li><code>Mythology</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>language</td>
	<td>Language</td>
	<td><a href="https://www.loc.gov/standards/iso639-2/php/code_list.php">ISO 639-2/3</a></td>
	<td>M</td>
	<td>R</td>
	<td>Use the appropriate language code for the material based on ISO 639-2/3.</td>
	<td>
		<ul>
			<li><code>eng</code> / English</li>
		</ul>
	</td>
</tr>

<tr>
	<td>rights</td>
	<td>Rights</td>
	<td></td>
	<td>M</td>
	<td>NR</td>
	<td>Provide a free-text rights statement describing copyright or permission information. Include copyright holders and year if provided. Use exact wording from the source site when available.</td>
	<td>
		<ul>
			<li><code>Content compilation © 2020, by the American Antiquarian Society. All rights reserved.</code></li>
			<li><code>Public domain in the USA</code></li>
		</ul>
	</td>
</tr>

<tr>
	<td>rightsstatement</td>
	<td>Rights</td>
	<td><a href="https://rightsstatements.org/page/1.0/?language=en">RightsStatements.org</a></td>
	<td>M</td>
	<td>NR</td>
	<td>Provide the standardized URI indicating copyright or license status.</td>
	<td>
		<ul>
			<li><code>http://rightsstatements.org/vocab/InC/1.0/</code></li>
		</ul>
	</td>
</tr>

</tbody>
</table>
</div>

<div>
<h2>Legend</h2>
<ul>
<li><code>M</code> Mandatory</li>
<li><code>RA</code> Required if Applicable</li>
<li><code>Rec</code> Recommended</li>
<li><code>Opt</code> Optional</li>
<li><code>R</code> Repeatable</li>
<li><code>NR</code> Not repeatable</li>
</ul>
</div>
</div>
