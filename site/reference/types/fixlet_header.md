# type: fixlet_header

Fixlet headers are name:value pairs that can provide important information about the Fixlet messages at any site. These inspectors only work in the context of property evaluation, not Fixlet evaluation.

# name of &lt;fixlet_header&gt;

Headers are name:value pairs, separated by a colon. This inspector returns the name on the left hand side of the pair.

# value of &lt;fixlet_header&gt;

Headers are name:value pairs, separated by a colon. This inspector returns the value on the right hand side of the pair.Example: number of relevant fixlets whose (value of header &quot;x-fixlet-source-severity&quot; of it as lowercase = &quot;critical&quot;) of site &quot;enterprise security&quot;. - Returns the number of critical fixlets in the Enterprise Security site.