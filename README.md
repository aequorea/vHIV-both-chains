# vHIV
An HIV vaccine (illustrating designed glycosylation as a means of epitope focusing)
<p align="center">
  <img src="vHIV.png" width="500"/>
</p>
<p align="center">
  vHIV (salmon and red) shown bound to N6 heavy and light chains (blue and yellow)
</p>
<p align="center">
  Potential glycosylation sites selected by gly21 software on the gp120 monomer are shown in red.
</p>
<p align="center">
  (based on 5TE4.PDB -- DOI:10.1016/j.immuni.2016.10.027)
</p>
<p>
After seeing the zHIV neutralizer on my computer screen for the first time, one of the first questions that came to mind was whether or not it would be possible to make more molecules like that one. The neutralizer was derived from the N6 antibody, which aside from the fact that it can neutralize some 98% of all HIV isolates it was tested against, has the interesting property that the light chain had evolved in such a way that it essentially stayed out of the way with the majority of the binding interaction being between the heavy chain and HIV's gp120 protein. This feature of N6 was used to make the small molecule HIV neutralizer zHIV.

Although initally I was thinking along the lines of trying to find a way to do high speed screening of a combinitorial antibody library to find single chain binders, eventually I started to wonder if it would be possible to trick the immune system into making antibodies that bind mostly with one chain or the other. Then I began to think that maybe vaccine design is somehow the "inverse" of neutralizer design, and with the ability to design new glycans into an antigen one might somehow "focus" the immunogenicity of that antigen such that the response would be a single chain binder.
</p>
<p>
It's easy enough to play this game using the crystal structure I used to do the zHIV neutralizer design. Just glycosylate gp120 instead of the antibody fragment leaving the portion of the gp120 to which the antibody is bound unglycosylated. This is shown above.
</p>
<p>
Interestingly, work has been proceeding along these lines using gp120's built in glycosylation sites and selective deglycosylation in the vicinity of the CD4 binding site (DOI:10.1016/j.celrep.2017.04.013). Gp120 trimers that are completely glycosylated show very little immunogenicity. If however, glycans in the vicinity of the CD4 binding site were removed, the trimers became immunogenic. The nature of the antibody binding in the selective deglycosylation experiments was not sufficiently characterized to determine if any were single chain binders, although there were some indications of neutralization broadness. So I think this idea of "focused immunogenicity" deserves further exploration. This might include glycoengineering not only of the location of the glycans but expression system engineering to better control glycan composition.
</p>
