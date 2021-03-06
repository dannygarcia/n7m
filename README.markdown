n7m.js
======

A lightweight javascript date library for converting plain text to numeronyms.

## The best way to minify your text

One of the biggest concerns with web development is filesize. We have javascript minifiers, css minifiers, whitespace removal, and gzip, but what about human readable text? Up until now, no library has been written to help with minifying human text. Enter n7m.js.

n7m.js converts your lengthy body copy into terse numeronyms. If you are a developer, chances are you're already familiar with numeronyms like 'i18n', 'a11y', and 'l10n'. Now, that brevity can be spread across the web with ease.

    npm install n7m

n7m works by converting strings greater than 2 characters in length to their numeronym counterpart.

    n7m('a'); // 'a'
    n7m('at'); // 'at'
    n7m('ace'); // 'ace'
    n7m('able'); // 'a2e'
    n7m('numeronym'); // 'n7m'
    n7m('numeronym'); // 'n7m'
    n7m('Pneumonoultramicroscopicsilicovolcanoconiosis'); // 'P43s'

## Filesize savings

n7m.js shaved off 36% of the Declaration of Independance. The bigger the words, the bigger the savings!

### Declaration of Independance

> When in the Course of human events it becomes necessary for one people to dissolve the political bands which have connected them with another and to assume among the powers of the earth, the separate and equal station to which the Laws of Nature and of Nature's God entitle them, a decent respect to the opinions of mankind requires that they should declare the causes which impel them to the separation.
> 
> We hold these truths to be self-evident, that all men are created equal, that they are endowed by their Creator with certain unalienable Rights, that among these are Life, Liberty and the pursuit of Happiness. — That to secure these rights, Governments are instituted among Men, deriving their just powers from the consent of the governed, — That whenever any Form of Government becomes destructive of these ends, it is the Right of the People to alter or to abolish it, and to institute new Government, laying its foundation on such principles and organizing its powers in such form, as to them shall seem most likely to effect their Safety and Happiness. Prudence, indeed, will dictate that Governments long established should not be changed for light and transient causes; and accordingly all experience hath shewn that mankind are more disposed to suffer, while evils are sufferable than to right themselves by abolishing the forms to which they are accustomed. But when a long train of abuses and usurpations, pursuing invariably the same Object evinces a design to reduce them under absolute Despotism, it is their right, it is their duty, to throw off such Government, and to provide new Guards for their future security. — Such has been the patient sufferance of these Colonies; and such is now the necessity which constrains them to alter their former Systems of Government. The history of the present King of Great Britain is a history of repeated injuries and usurpations, all having in direct object the establishment of an absolute Tyranny over these States. To prove this, let Facts be submitted to a candid world.
> 
> He has refused his Assent to Laws, the most wholesome and necessary for the public good.
> 
> He has forbidden his Governors to pass Laws of immediate and pressing importance, unless suspended in their operation till his Assent should be obtained; and when so suspended, he has utterly neglected to attend to them.
> 
> He has refused to pass other Laws for the accommodation of large districts of people, unless those people would relinquish the right of Representation in the Legislature, a right inestimable to them and formidable to tyrants only.
> 
> He has called together legislative bodies at places unusual, uncomfortable, and distant from the depository of their Public Records, for the sole purpose of fatiguing them into compliance with his measures.
> 
> He has dissolved Representative Houses repeatedly, for opposing with manly firmness his invasions on the rights of the people.
> 
> He has refused for a long time, after such dissolutions, to cause others to be elected, whereby the Legislative Powers, incapable of Annihilation, have returned to the People at large for their exercise; the State remaining in the mean time exposed to all the dangers of invasion from without, and convulsions within.
> 
> He has endeavoured to prevent the population of these States; for that purpose obstructing the Laws for Naturalization of Foreigners; refusing to pass others to encourage their migrations hither, and raising the conditions of new Appropriations of Lands.
> 
> He has obstructed the Administration of Justice by refusing his Assent to Laws for establishing Judiciary Powers.
> 
> He has made Judges dependent on his Will alone for the tenure of their offices, and the amount and payment of their salaries.
> 
> He has erected a multitude of New Offices, and sent hither swarms of Officers to harass our people and eat out their substance.
> 
> He has kept among us, in times of peace, Standing Armies without the Consent of our legislatures.
> 
> He has affected to render the Military independent of and superior to the Civil Power.
> 
> He has combined with others to subject us to a jurisdiction foreign to our constitution, and unacknowledged by our laws; giving his Assent to their Acts of pretended Legislation:
> 
> For quartering large bodies of armed troops among us:
> 
> For protecting them, by a mock Trial from punishment for any Murders which they should commit on the Inhabitants of these States:
> 
> For cutting off our Trade with all parts of the world:
> 
> For imposing Taxes on us without our Consent:
> 
> For depriving us in many cases, of the benefit of Trial by Jury:
> 
> For transporting us beyond Seas to be tried for pretended offences:
> 
> For abolishing the free System of English Laws in a neighbouring Province, establishing therein an Arbitrary government, and enlarging its Boundaries so as to render it at once an example and fit instrument for introducing the same absolute rule into these Colonies
> 
> For taking away our Charters, abolishing our most valuable Laws and altering fundamentally the Forms of our Governments:
> 
> For suspending our own Legislatures, and declaring themselves invested with power to legislate for us in all cases whatsoever.
> 
> He has abdicated Government here, by declaring us out of his Protection and waging War against us.
> 
> He has plundered our seas, ravaged our coasts, burnt our towns, and destroyed the lives of our people.
> 
> He is at this time transporting large Armies of foreign Mercenaries to compleat the works of death, desolation, and tyranny, already begun with circumstances of Cruelty & Perfidy scarcely paralleled in the most barbarous ages, and totally unworthy the Head of a civilized nation.
> 
> He has constrained our fellow Citizens taken Captive on the high Seas to bear Arms against their Country, to become the executioners of their friends and Brethren, or to fall themselves by their Hands.
> 
> He has excited domestic insurrections amongst us, and has endeavoured to bring on the inhabitants of our frontiers, the merciless Indian Savages whose known rule of warfare, is an undistinguished destruction of all ages, sexes and conditions.
> 
> In every stage of these Oppressions We have Petitioned for Redress in the most humble terms: Our repeated Petitions have been answered only by repeated injury. A Prince, whose character is thus marked by every act which may define a Tyrant, is unfit to be the ruler of a free people.
> 
> Nor have We been wanting in attentions to our British brethren. We have warned them from time to time of attempts by their legislature to extend an unwarrantable jurisdiction over us. We have reminded them of the circumstances of our emigration and settlement here. We have appealed to their native justice and magnanimity, and we have conjured them by the ties of our common kindred to disavow these usurpations, which would inevitably interrupt our connections and correspondence. They too have been deaf to the voice of justice and of consanguinity. We must, therefore, acquiesce in the necessity, which denounces our Separation, and hold them, as we hold the rest of mankind, Enemies in War, in Peace Friends.
> 
> We, therefore, the Representatives of the united States of America, in General Congress, Assembled, appealing to the Supreme Judge of the world for the rectitude of our intentions, do, in the Name, and by Authority of the good People of these Colonies, solemnly publish and declare, That these united Colonies are, and of Right ought to be Free and Independent States, that they are Absolved from all Allegiance to the British Crown, and that all political connection between them and the State of Great Britain, is and ought to be totally dissolved; and that as Free and Independent States, they have full Power to levy War, conclude Peace, contract Alliances, establish Commerce, and to do all other Acts and Things which Independent States may of right do. — And for the support of this Declaration, with a firm reliance on the protection of Divine Providence, we mutually pledge to each other our Lives, our Fortunes, and our sacred Honor.";

### n7m Declaration of Independance

> W2n in t1e C4e of h3n e4s it b5s n7y f1r o1e p4e to d6e t1e p7l b3s w3h h2e c7d t2m w2h a5r a1d to a4e a3g t1e p4s of t1e e3h, t1e s6e a1d e3l s5n to w3h t1e L2s of N4e a1d of N4e's G1d e5e t2m, a d4t r5t to t1e o6s of m5d r6s t2t t2y s4d d5e t1e c4s w3h i3l t2m to t1e s8n.We h2d t3e t4s to be s2f-e5t, t2t a1l m1n a1e c5d e3l, t2t t2y a1e e5d by t3r C5r w2h c5n u9e R4s, t2t a3g t3e a1e L2e, L5y a1d t1e p5t of H7s. — T2t to s4e t3e r4s, G9s a1e i8d a3g M1n, d6g t3r j2t p4s f2m t1e c5t of t1e g6d, — T2t w6r a1y F2m of G8t b5s d9e of t3e e2s, it is t1e R3t of t1e P4e to a3r or to a5h it, a1d to i7e n1w G8t, l4g i1s f8n on s2h p8s a1d o8g i1s p4s in s2h f2m, as to t2m s3l s2m m2t l4y to e4t t3r S4y a1d H7s. P6e, i4d, w2l d5e t2t G9s l2g e9d s4d n1t be c5d f1r l3t a1d t7t c4s; a1d a9y a1l e8e h2h s3n t2t m5d a1e m2e d6d to s4r, w3e e3s a1e s8e t2n to r3t t8s by a8g t1e f3s to w3h t2y a1e a8d. B1t w2n a l2g t3n of a4s a1d u9s, p6g i8y t1e s2e O4t e5s a d4n to r4e t2m u3r a6e D7m, it is t3r r3t, it is t3r d2y, to t3w o1f s2h G8t, a1d to p5e n1w G4s f1r t3r f4e s6y. — S2h h1s b2n t1e p5t s8e of t3e C6s; a1d s2h is n1w t1e n7y w3h c8s t2m to a3r t3r f4r S5s of G8t. T1e h5y of t1e p5t K2g of G3t B5n is a h5y of r6d i6s a1d u9s, a1l h4g in d4t o4t t1e e11t of an a6e T5y o2r t3e S4s. To p3e t2s, l1t F3s be s7d to a c4d w3d.He h1s r5d h1s A4t to L2s, t1e m2t w7e a1d n7y f1r t1e p4c g2d.He h1s f7n h1s G7s to p2s L2s of i7e a1d p6g i8e, u4s s7d in t3r o7n t2l h1s A4t s4d be o6d; a1d w2n so s7d, he h1s u5y n7d to a4d to t2m.He h1s r5d to p2s o3r L2s f1r t1e a11n of l3e d7s of p4e, u4s t3e p4e w3d r8h t1e r3t of R12n in t1e L9e, a r3t i9e to t2m a1d f8e to t5s o2y.He h1s c4d t6r l9e b4s at p4s u5l, u11e, a1d d5t f2m t1e d8y of t3r P4c R5s, f1r t1e s2e p5e of f7g t2m i2o c8e w2h h1s m6s.He h1s d7d R12e H4s r8y, f1r o6g w2h m3y f6s h1s i7s on t1e r4s of t1e p4e.He h1s r5d f1r a l2g t2e, a3r s2h d10s, to c3e o4s to be e5d, w5y t1e L9e P4s, i7e of A10n, h2e r6d to t1e P4e at l3e f1r t3r e6e; t1e S3e r7g in t1e m2n t2e e5d to a1l t1e d5s of i6n f2m w5t, a1d c9s w4n.He h1s e9d to p5t t1e p8n of t3e S4s; f1r t2t p5e o9g t1e L2s f1r N12n of F8s; r6g to p2s o4s to e7e t3r m8s h4r, a1d r5g t1e c8s of n1w A12s of L3s.He h1s o8d t1e A12n of J5e by r6g h1s A4t to L2s f1r e10g J7y P4s.He h1s m2e J4s d7t on h1s W2l a3e f1r t1e t4e of t3r o5s, a1d t1e a4t a1d p5t of t3r s6s.He h1s e5d a m7e of N1w O5s, a1d s2t h4r s4s of O6s to h4s o1r p4e a1d e1t o1t t3r s7e.He h1s k2t a3g us, in t3s of p3e, S6g A4s w5t t1e C5t of o1r l10s.He h1s a6d to r4r t1e M6y i9t of a1d s6r to t1e C3l P3r.He h1s c6d w2h o4s to s5t us to a j10n f5n to o1r c10n, a1d u12d by o1r l2s; g4g h1s A4t to t3r A2s of p7d L9n:F1r q8g l3e b4s of a3d t4s a3g us:F1r p8g t2m, by a m2k T3l f2m p8t f1r a1y M5s w3h t2y s4d c4t on t1e I9s of t3e S4s:F1r c5g o1f o1r T3e w2h a1l p3s of t1e w3d:F1r i6g T3s on us w5t o1r C5t:F1r d7g us in m2y c3s, of t1e b5t of T3l by J2y:F1r t10g us b4d S2s to be t3d f1r p7d o6s:F1r a8g t1e f2e S4m of E5h L2s in a n10g P6e, e10g t5n an A7y g8t, a1d e7g i1s B8s so as to r4r it at o2e an e5e a1d f1t i8t f1r i9g t1e s2e a6e r2e i2o t3e C9r t4g a2y o1r C6s, a8g o1r m2t v6e L2s a1d a6g f11y t1e F3s of o1r G9s:F1r s8g o1r o1n L10s, a1d d7g t8s i6d w2h p3r to l7e f1r us in a1l c3s w8r.He h1s a7d G8t h2e, by d7g us o1t of h1s P8n a1d w4g W1r a5t us.He h1s p7d o1r s2s, r5d o1r c4s, b3t o1r t3s, a1d d7d t1e l3s of o1r p4e.He is at t2s t2e t10g l3e A4s of f5n M9s to c6t t1e w3s of d3h, d8n, a1d t5y, a5y b3n w2h c11s of C5y & P5y s6y p8d in t1e m2t b7s a2s, a1d t5y u6y t1e H2d of a c7d n4n.He h1s c9d o1r f4w C6s t3n C5e on t1e h2h S2s to b2r A2s a5t t3r C5y, to b4e t1e e10s of t3r f5s a1d B6n, or to f2l t8s by t3r H3s.He h1s e5d d6c i11s a5t us, a1d h1s e9d to b3g on t1e i9s of o1r f7s, t1e m7s I4n S5s w3e k3n r2e of w5e, is an u13d d9n of a1l a2s, s3s a1d c8s.In e3y s3e of t3e O9s We h2e P8d f1r R5s in t1e m2t h4e t3s: O1r r6d P7s h2e b2n a6d o2y by r6d i4y. A P4e, w3e c7r is t2s m4d by e3y a1t w3h m1y d4e a T4t, is u3t to be t1e r3r of a f2e p4e.N1r h2e We b2n w5g in a8s to o1r B5h b6n. We h2e w4d t2m f2m t2e to t2e of a6s by t3r l9e to e4d an u11e j10n o2r us. We h2e r6d t2m of t1e c11s of o1r e8n a1d s8t h2e. We h2e a6d to t3r n4e j5e a1d m9y, a1d we h2e c6d t2m by t1e t2s of o1r c4n k5d to d5w t3e u9s, w3h w3d i8y i7t o1r c9s a1d c12e. T2y t1o h2e b2n d2f to t1e v3e of j5e a1d of c11y. We m2t, t7e, a7e in t1e n7y, w3h d7s o1r S8n, a1d h2d t2m, as we h2d t1e r2t of m5d, E5s in W1r, in P3e F5s.We, t7e, t1e R13s of t1e u4d S4s of A5a, in G5l C6s, A7d, a7g to t1e S5e J3e of t1e w3d f1r t1e r7e of o1r i8s, do, in t1e N2e, a1d by A7y of t1e g2d P4e of t3e C6s, s6y p5h a1d d5e, T2t t3e u4d C6s a1e, a1d of R3t o3t to be F2e a1d I9t S4s, t2t t2y a1e A6d f2m a1l A8e to t1e B5h C3n, a1d t2t a1l p7l c8n b5n t2m a1d t1e S3e of G3t B5n, is a1d o3t to be t5y d7d; a1d t2t as F2e a1d I9t S4s, t2y h2e f2l P3r to l2y W1r, c6e P3e, c6t A7s, e7h C6e, a1d to do a1l o3r A2s a1d T4s w3h I9t S4s m1y of r3t do. — A1d f1r t1e s5t of t2s D9n, w2h a f2m r6e on t1e p8n of D4e P8e, we m6y p4e to e2h o3r o1r L3s, o1r F6s, a1d o1r s4d H3r.";

