Test
====

[somelik](/doc)

<div itemtype="http://mosai.org/parcel" itemscope="itemscope">
	This code is on the
	<code itemprop="lib">/blablabla</code> path on
	<a itemprop="archive"
	   href="https://github.com/alganet/testing/archive/master.zip">
	   this zip
	</a>.
</div>

<div xmlns="http://www.w3.org/1999/xhtml"
  prefix="
    : http://mosai.org/ns/part#
    rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
    rdfs: http://www.w3.org/2000/01/rdf-schema#"
  >
  <div typeof="rdfs:Resource" about="http://mosai.org/ns/mosai/workshop">
  	<meta property=":about" content="A Collection of POSIX Shell Tools" />
    <div property=":about" content="A Collection of POSIX Shell Tools"></div>
    <div rel=":dependsOn" resource="http://mosai.org/ns/mosai/trix"></div>
    <div rel=":dependsOn" resource="http://mosai.org/ns/mosai/posit"></div>
    <div rel=":dependsOn">
      <div typeof="rdfs:Resource" about="http://mosai.org/ns/mosai/answer">
        <div property=":about" content="An Interactive POSIX Shell Command Line Interface"></div>
        <div rel=":dependsOn" resource="http://mosai.org/ns/mosai/common"></div>
        <div rel=":dependsOn" resource="http://mosai.org/ns/mosai/dispatch"></div>
      </div>
    </div>
    <div rel=":dependsOn" resource="http://mosai.org/ns/mosai/depur"></div>
  </div>
  <div typeof="rdfs:Resource" about="http://mosai.org/ns/mosai/common">
    <div property=":about" content="Common Compatibility Settings for Portable Shell Scripts"></div>
    <div rel=":library">
      <div typeof=":ShellScript" about="http://rdf-translator.appspot.com/lib/common.sh">
      </div>
    </div>
  </div>
</div>
