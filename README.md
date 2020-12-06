# cmc-core

Customisation for CMC dokuments and corpora using the TEI

cmc-core.odd describes an encoding schema for genres of computer-mediated communication                                                                                                          
                (CMC) / social media. It is meant to define a basic setup that one needs to encode                                                                                                           
                CMC corpora, but which is not in the TEI yet.
                
CUSTOMIZATION:

            The schema introduces four types of customizations:
             - (1) A new module named 'cmc' is introduced. It is referenced by the new                                                                                                            
                        model classe model.divPart.cmc, by the new attribute class att.global.cmc,                                                                                                           
                        and by the new element post.             
             - (2) The new element post is introduced.
             - (3) The new attribute class att.global.cmc is introduced. It defines the                                                                                                           
                   new global attribute creation. The existing attribute class                                                                                                               
                   att.global has been modified to additionally be a member of                                                                                                                          
                   att.global.cmc.item
             - (4) The class model.divPart.cmc is defined. model.divPart.cmc is a member                                                                                                          
                   of model.divPart and serves as a container of the new, CMC-specific element                                                                                                          
                   post

            In addition to these customizations, we have provided sample annotations using this                                                                                                          
            schema and covering various genres, i.e. private chat, IRC, twitter, Second Life,                                                                                                            
            and Wikipedia talk.
