---
layout: sidebar
sidebar: s1
title: "The MEI Header"
sectionid: "header"
---

<span class="div">
   
   <h1 id="header">
      <span class="headingNumber">2</span>
      <span class="head">The MEI Header</span>
   </h1>
   This chapter addresses the description of an encoded item so that the musical text,
   as well as
   its sources, encoding, and revisions are all thoroughly documented. Such documentation
   is
   necessary for scholars using the texts, for software processing them, and for catalogers
   in
   libraries and archives. Together these descriptions and declarations provide an electronic
   analog to the title page attached to a printed work. They also constitute an equivalent
   for the
   content of the code books or introductory manuals customarily accompanying electronic
   data
   sets.
   
   Every MEI-conformant text not embedded in another XML carrier that provides for capturing
   metadata, such as TEI or METS, must carry a set of descriptions, prefixed to it and
   encoded as
   described in this chapter. This set is known as the MEI header, tagged 
   <a class="link_odd_elementSpec" href="/v3/elements/meiHead">meiHead</a>, and has five major parts:
   
   
   <span class="list">
      
      <span class="item">one or more alternative identifiers, tagged with 
         <a class="link_odd_elementSpec" href="/v3/elements/altId">altId</a>, each of
         which provides an identifying name or number associated with the file.
      </span>
      
      <span class="item">a file description, tagged 
         <a class="link_odd_elementSpec" href="/v3/elements/fileDesc">fileDesc</a>, containing a full
         bibliographic description of the computer file itself, from which a user of the text
         could
         derive a proper bibliographic citation, or which a librarian or archivist could use
         in
         creating a catalog entry recording its presence within a library or archive. The term
         computer file here is to be understood as referring to the whole intellectual
         entity or document described by the header, even when this is stored in multiple physical
         operating system files. The file description also includes information about the source
         or
         sources from which the electronic document was derived. The MEI elements used to encode
         the
         file description are described in section 
         <span class="ptr"></span> below.
      </span>
      
      <span class="item">an encoding description, tagged 
         <a class="link_odd_elementSpec" href="/v3/elements/encodingDesc">encodingDesc</a>, which
         describes the relationship between an electronic text and its source or sources. It
         allows for
         detailed description of whether (or how) the text was normalized during transcription,
         how the
         encoder resolved ambiguities in the source, what levels of encoding or analysis were
         applied,
         and similar matters. The MEI elements used to encode the encoding description are
         described in
         section 
         <span class="ptr"></span> below.
      </span>
      
      <span class="item">a work description, tagged 
         <a class="link_odd_elementSpec" href="/v3/elements/workDesc">workDesc</a>, containing
         classification and contextual information about the work, such as its subject matter,
         the
         situation in which it was produced, the individuals described by or participating
         in producing
         it, and so forth. Such a work profile is of particular use in highly structured composite
         texts such as corpora or language collections, where it is often highly desirable
         to enforce a
         controlled descriptive vocabulary or to perform retrievals from a body of text in
         terms of
         text type or origin. The work description may however be of use in any form of automatic
         text
         processing. The MEI elements used to encode the work description are described in
         section 
         <span class="ptr"></span> below.
      </span>
      
      <span class="item">a revision history, tagged 
         <a class="link_odd_elementSpec" href="/v3/elements/revisionDesc">revisionDesc</a>, which allows
         the encoder to provide a history of changes made during the development of the electronic
         text. The revision history is important for version control and for resolving
         questions about the history of a file. The MEI elements used to encode the revision
         description are described in section 
         <span class="ptr"></span> below.
      </span>
      
   </span>
   
   
   
   
   
   
   
   
</span>