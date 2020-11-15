## ST. CLAIRE LICENSE

***Please note that this version of the St. Claire License is not stable, has not undergone formal legal review, and should not be used to license projects in its current form.***

***Constructive commentary and feedback on the license, particularly around the phrasing of the ethical clauses text, is welcome and appreciated.***

The St. Claire License aims to provide developers with a legally-enforceable avenue for ensuring that their work is not utilized in a manner that directly conflicts with specific ethical beliefs, while providing others with the freedom to use the work in all other cases. It is primarily aimed at projects in the machine learning domain. 

## Frequently Asked Questions

### Q: Should I use the St. Claire License?

**Short:** Maybe.

**Long:** If you would otherwise use a permissive license like the MIT or Apache 2.0, have very specific things that you don't want your open source code to be used for, work in the machine learning domain, and see alignment between the St. Claire License's ethical clauses and your own values, you may want to consider using the St. Claire License. 

Alternatively, you may want to try using the Extended St. Claire License Template to write your own license. Should you decide to do so, it's likely you may want the final license text to be formally reviewed by a legal counsel. 

### Q: Is the St. Claire License open source?

**Short:** No. The St. Claire License does not meet the OSI's definition for Open Source, due to "discrimination against fields of endeavor", which is the main feature of the St. Claire License in the form of the ethical clauses.

**Long:** The St. Claire License doesn't meet the criteria for uppercase "Open Source", but it can probably be considered lower-case "open source". The license itself conforms with all aspects of the OSI's [Open Source Defintion](https://opensource.org/osd) except for Section 6: No Discrimination Against Fields of Endeavor. 

Furthermore, the St. Claire License generally passes the corner-cases often used by the Debian Free Software Guidelines (see Section 9 [here](https://people.debian.org/~bap/dfsg-faq.html)), including the Desert Island Test, Dissident Test, and Tentacles of Evil Test. The Dissident Test may be failed if a dissident wanted to hide their possession of St. Claire-licensed software behind a remote network interaction, but this is largely a grey-area in existing conversations around the AGPLv3 anyway, so you probably don't need to worry about it. 

A license based on the Extended St. Claire Template may be used in such a way that it fails any of these tests via poorly or maliciously-written ethical clauses, but the Standard version passes. Anyone considering using software under a license generated via the Extended St. Claire Template should take extra care to make sure they understand the terms set by that particular license's author(s).  

### Q: Is the St. Claire License copyleft?

**S:** No.

**L:** No. The St. Claire License has no requirement to provide either the modified or original source code. However, there is language more aggressively requiring that a copyright notice and associated list of conditions be included with the software and its artifacts, including when they accessed through a remote network interaction. This requirement is similar to the AGPLv3 requirement, sans source code.

### Q: Is the St. Claire License in the [SPDX License Registry](https://spdx.dev/ids/)?

**S:** Not yet.

**L:** Not yet. This license has not undergone final revision or formal legal review. Once those have taken place, the plan is to submit the St. Claire License for inclusion in the SPDX List. Since licenses like the Hippocratic License are included, the ethical clause restrictions in the St. Claire License is not expected to cause an issue with acceptance. 

### Q: Can I use the St. Claire License to make money off my open source project?

**S:** Probably not directly. Making money off of open source projects is complicated, but would probably require dual-licensing.  

**L:** There are many discussions about routes for making money off of open source projects, but many of them can be viewed through an "insert license name here", where the St. Claire License would be grouped with most generally permissive licenses like MIT or Apache 2.0, not with copyleft ones like A/GPLv3. There's no language preventing dual-licensing a piece of software under both the St. Claire and a commercial license.

However, I encourage developers choosing this route to use language in the commercial license to maintain some degree of consideration to the ethics of the end use cases, such as creating exceptions to the ethical clauses for only specific use cases.

### Q: What's the difference between the St. Claire License and the Extended St. Claire Template?

The St. Claire License is primarily aimed at software in machine learning domain, and as such has domain-specific language and ethical clauses for that area. The Extended St. Claire Template is an acknowledgement that this approach may be useful in other fields, and provides a basis for developers to write their own ethical clauses. I ask that any developer using the Extended St. Claire Template to write their own license put in an effort to clarify that their license **is not** the standard St. Claire License by prominently declaring it to be an Extended version An example of this could be: 

> This software is licensed under the Extended St. Claire License with modified restrictive language. Please take the time to read the license and make sure you understand the list of conditions for using this software. 

### Q: Are there other examples of licenses like this?

Yes. In fact, the Ethical Clauses are adapted from language found in the [Responsible AI License](https://www.licenses.ai/open-source-license) (RAIL). In addition, other domain-specific licenses like the [Cryptographic Autonomy License](https://github.com/holochain/cryptographic-autonomy-license) exist, along with more general "ethical" licenses like the [Hippocratic License](https://firstdonoharm.dev/) and others. Information on more of these can found at [ethicalsource.dev](https://ethicalsource.dev/licenses/). One of the most well-known examples of a license with an ethical clause is the [JSON License](https://json.org/license.html) ("This Software shall be usd for Good, not Evil"), although it is widely-regarded as too vague to be safely used by third-party organizations, since Good and Evil are generally subjective terms.

### Q: Then why not use one of those?

**S:** They're not exactly what I wanted. Maybe they're not exactly what you want, either. 

**L:** It would take too long to list every reason why each one of the existing licenses don't scratch my itch. Some of them include U.S.-centric language, odd enforcement terms, language I believe is either too generic or restrictive, etc. 

### Q: Why is it called the St. Claire License?

This is a potentially whimsical reference to [*The Good Place*](https://en.wikipedia.org/wiki/The_Good_Place), which I think creates a nice semi-parable of a specially-created middle ground tailored to a specific situation, until problems can be addressed at a systemic level. Also, Kristen Bell is a national treasure.
