Regex Extractor:
	1. Using Regex to Extract desired data
	2. Used for Structured Documents

DOM:
   Contains information about document structure
	1. Pages - Page Index, Size, Length
	2. Sections - Language, Rotation, Type(Header, Footer, Table, Paragraph)
	3. Word Groups
	4. Word - Position, Index in Text, OCR Confidence, Text or Word itself.

Form Extractor:
	1. Uses world's Position information to extract data
	2. Used for documents with fixed format
	3. We can configure templates for our documents.
	4. For every document type template defination is checked
	5. Best matching template is picked and data is extracted
	6. Community endpoint requests limited to 50/hr