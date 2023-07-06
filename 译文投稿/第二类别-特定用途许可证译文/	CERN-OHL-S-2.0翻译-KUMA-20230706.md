译者注：本人KUMA（xyqgz123[at]sina.com）承诺，该译文系本人原创翻译。本人同意，如本人译文被开放原子开源基金会开源许可证翻译项目选为终版译本，本人同意将译文以CC0协议贡献至公有领域。本许可证原文链接:https://ohwr.org/cern_ohl_s_v2.pdf


### CERN Open Hardware Licence Version 2 - Strongly Reciprocal

### CERN开放硬件许可证第2版—强互惠型



 **Preamble** 

 **序言** 

CERN has developed this licence to promote collaboration among hardware designers and to provide a legal tool which supports the freedom to use, study, modify, share and distribute hardware designs and products based on those designs. Version 2 of the CERN Open Hardware Licence comes in three variants: CERN-OHL-P (permissive); and two reciprocal licences: CERN-OHL-W (weakly reciprocal) and this licence, CERN-OHL-S (strongly reciprocal).

欧洲核子研究中心制定了本许可证，以促进硬件设计者之间的合作，并为支持自由使用、研究、修改、共享和分发硬件设计以及基于此设计的产品提供一个法律工具。CERN开放硬件许可证第2版有三个变体： CERN-OHL-P（宽松型）；以及两个互惠型许可证： CERN-OHL-W（弱互惠型）和本许可证，CERN-OHL-S（强互惠型）。

The CERN-OHL-S is copyright CERN 2020. Anyone is welcome to use it, in unmodified form only.

CERN-OHL-S的版权自2020年归CERN 所有。欢迎任何人使用此许可证，但仅允许以原样不作任何修改的形式使用。

Use of this Licence does not imply any endorsement by CERN of any Licensor or their designs nor does it imply any involvement by CERN in their development.

使用本许可证并不意味着CERN认可任何许可人或其设计，也不意味着CERN参与其开发。

 **1 Definitions** 

 **1 定义** 

1.1 'Licence' means this CERN-OHL-S.

1.1 “许可证”指本CERN-OHL-S许可证。

1.2 'Compatible Licence' means

1.2 “兼容许可证”是指

    a) any earlier version of the CERN Open Hardware licence, or 

    a）任何CERN开放硬件许可证的早期版本，或

    b) any version of the CERN-OHL-S, or 

    b) 任何版本的CERN-OHL-S，或

    c) any licence which permits You to treat the Source to which it applies as licensed under CERN-OHL-S provided that on Conveyance of any such Source, or any associated Product You treat the Source in question as being licensed under CERN-OHL-S.

    c) 任何允许您将其适用的源视为以CERN-OHL-S进行许可的许可证，只要您在传递此类源或任何相关的产品时，将上述源视为以CERN-OHL-S进行许可。

1.3 'Source' means information such as design materials or digital code which can be applied to Make or test a Product or to prepare a Product for use, Conveyance or sale, regardless of its medium or how it is expressed. It may include Notices.

1.3 “源”是指用于制造或者测试产品或用于准备产品的使用、传递或销售的信息，如设计材料或数字代码，不论此种信息的媒介或表达方式为何。它可以包括声明。

1.4 'Covered Source' means Source that is explicitly made available under this Licence.

1.4 “受保护源”是指根据本许可证明确提供的源。

1.5 'Product' means any device, component, work or physical object, whether in finished or intermediate form, arising from the use, application or processing of Covered Source.

1.5 “产品”是指通过使用、应用或处理受保护源所产生的任何成品或者中间态的设备、部件、作品或实物。

1.6 'Make' means to create or configure something, whether by manufacture, assembly, compiling, loading or applying Covered Source or another Product or otherwise.

1.6 “制造”是指通过生产、组装、编译、加载或应用受保护源或其他产品或以其他方式，创造或配置某种东西。

1.7 'Available Component' means any part, sub-assembly, library or code which:

1.7 “可用部件”是指任何部件、组件、库或代码，它们是

    a) is licensed to You as Complete Source under a Compatible Licence; or

    a) 作为完整源以兼容许可证许可给您；或

    b) is available, at the time a Product or the Source containing it is first Conveyed, to You and any other prospective licensees

    b) 在包含该可用部件的产品或者源被首次传递时，以下列方式提供给您和任何其他潜在被许可人

           i) as a physical part with sufficient rights and information (including any configuration and programming files and information about its characteristics and interfaces) to enable it either to be Made itself, or to be sourced and used to Make the Product; or

           i) 作为实体部件，该实体部件具备充分的权利和信息（包括任何配置和编程文件以及关于其特征和接口的信息），从而能够制造此实体部件，或通过反向工程将其用于制造产品；或

           ii) as part of the normal distribution of a tool used to design or Make the Product.

           ii) 作为设计或制造产品的工具正常分发的一部分。

1.8 'Complete Source' means the set of all Source necessary to Make a Product, in the preferred form for making modifications, including necessary installation and interfacing information both for the Product, and for any included Available Components. If the format is proprietary, it must also be made available in a format (if the proprietary tool can create it) which is viewable with a tool available to potential licensees and licensed under a licence approved by the Free Software Foundation or the Open Source Initiative. Complete Source need not include the Source of any Available Component, provided that You include in the Complete Source sufficient information to enable a recipient to Make or source and use the Available Component to Make the Product.

1.8 完整源是指制造产品所需的所有源的集合，这些源以进行修改的首选形式呈现，包括对产品和任何包含的可用部件所必要的安装和接口信息。如果呈现形式是私有的，它必须再以另一种形式呈现，并且潜在被许可人可通过可获得的工具查看该形式（如果私有工具可以创建它），同时根据自由软件基金会或开放源代码促进会批准的许可证进行许可。完整源不需要包括任何可用部件的源，只要在完整源中包含足够的信息，使接收者能够制造或使用可用部件来制造产品。

1.9 'Source Location' means a location where a Licensor has placed Covered Source, and which that Licensor reasonably believes will remain easily accessible for at least three years for anyone to obtain a digital copy.

1.9 “源位置”是指许可人放置受保护源的位置，并且许可人有理由相信至少三年内任何人可以容易地从该位置获得数字副本。

1.10 'Notice' means copyright, acknowledgement and trademark notices, Source Location references, modification notices (subsection 3.3(b)) and all notices that refer to this Licence and to the disclaimer of warranties that are included in the Covered Source.

1.10 “声明”是指版权、致谢和商标声明、源位置引用、修改声明（第3.3(b)款）以及所有提及本许可证的声明和包含在受保护源中的免责声明。

1.11 'Licensee' or 'You' means any person exercising rights under this Licence.

1.11 “被许可人”或 “您”是指任何根据本许可证行使权利的人。

1.12 'Licensor' means a natural or legal person who creates or modifies Covered Source. A person may be a Licensee and a Licensor at the same time.

1.12 “许可人”指创建或修改受保护源的自然人或法人。一个人可以同时是被许可人和许可人。

1.13 'Convey' means to communicate to the public or distribute.

1.13 “传递”是指向公众传播或分发。

 **2 Applicability** 
 
 **2 适用性** 

2.1 This Licence governs the use, copying, modification, Conveying of Covered Source and Products, and the Making of Products. By exercising any right granted under this Licence, You irrevocably accept these terms and conditions.

2.1 本许可证约束受保护源和产品的使用、复制、修改、传递以及产品的制造。通过行使本许可证授予的任何权利，您不可撤销地接受这些条款和条件。

2.2 This Licence is granted by the Licensor directly to You, and shall apply worldwide and without limitation in time.

2.2 本许可证由许可人直接授予您，许可地域范围为全球范围内，许可时间无限制。

2.3 You shall not attempt to restrict by contract or otherwise the rights granted under this Licence to other Licensees.

2.3 您不应该试图通过合同或其他方式限制本许可授予其他被许可人的权利。

2.4 This Licence is not intended to restrict fair use, fair dealing, or any other similar right.

2.4 本许可证不打算限制公平使用、公平交易或任何其他类似的权利。

 **3 Copying, modifying and Conveying Covered Source** 

 **3 复制、修改和传递受保护源** 

3.1 You may copy and Convey verbatim copies of Covered Source, in any medium, provided You retain all Notices.

3.1 您可以在任何媒介上复制和传递受保护源的逐字副本，但您必须保留所有的声明。

3.2 You may modify Covered Source, other than Notices, provided that You irrevocably undertake to make that modified Covered Source available from a Source Location should You Convey a Product in circumstances where the recipient does not otherwise receive a copy of the modified Covered Source. In each case subsection 3.3 shall apply.

3.2 您可以修改除声明以外的受保护源，但您必须不可撤销地承诺，如果您在接收者没有收到修改后的受保护源副本的情况下传递产品，您将从源位置提供修改后的受保护源。在任何情况下，第3.3款都应适用。

You may only delete Notices if they are no longer applicable to the corresponding Covered Source as modified by You and You may add additional Notices applicable to Your modifications. Including Covered Source in a larger work is modifying the Covered Source, and the larger work becomes modified Covered Source.

您只能删除不再适用于您经修改的相应受保护源的声明，您可以添加适用于您的修改的额外声明。将受保护源纳入更大的作品中构成对受保护源的修改，而更大的作品则成为经修改的受保护源。

3.3 You may Convey modified Covered Source (with the effect that You shall also become a Licensor) provided that You: 

3.3 您可以传递经修改的受保护源（其效果是您也将成为许可人），但您必须

    a) retain Notices as required in subsection 3.2;

    a）按照第3.2款的要求保留声明；

    b) add a Notice to the modified Covered Source stating that You have modified it, with the date and brief description of how You have modified it;

    b）在经修改的受保护源上添加声明，说明您已经修改了该受保护源，同时注明日期并简要说明您是如何修改的；

    c) add a Source Location Notice for the modified Covered Source if You Convey in circumstances where the recipient does not otherwise receive a copy of the modified Covered Source; and
   
    c）在接收者没有收到经修改的受保护源副本的情况下，为经修改的受保护源添加一个源位置声明，

    d) license the modified Covered Source under the terms and conditions of this Licence (or, as set out in subsection 8.3, a later version, if permitted by the licence of the original Covered Source). Such modified Covered Source must be licensed as a whole, but excluding Available Components contained in it, which remain licensed under their own applicable licences.
    
    d）根据本许可证的条款和条件（或者按照第8.3款的规定，在原始受保护源的许可证允许的情况下，根据新版本的许可证）许可经修改的受保护源。此种经修改的受保护源必须作为整体进行许可，但不包括包含于其中的可用部件，这些部件仍然根据其自身适用的许可证进行许可。

 **4 Making and Conveying Products** 

 **4 制造和传递产品** 

You may Make Products, and/or Convey them, provided that You either provide each recipient with a copy of the Complete Source or ensure that each recipient is notified of the Source Location of the Complete Source. That Complete Source is Covered Source, and You must accordingly satisfy Your obligations set out in subsection 3.3. If specified in a Notice, the Product must visibly and securely display the Source Location on it or its packaging or documentation in the manner specified in that Notice.

您可以制造和/或传递产品，但您必须向所有接收者提供完整源的副本，或确保每个接收者被告知完整源的源位置。该完整源指受保护源，您必须相应地履行第3.3款规定的义务。如果声明中有阐明源位置，产品必须以该声明中阐明的方式在声明中或其包装或文件上明显和安全地载明源位置。

 **5 Research and Development** 

 **5 研究和开发** 

You may Convey Covered Source, modified Covered Source or Products to a legal entity carrying out development, testing or quality assurance work on Your behalf provided that the work is performed on terms which prevent the entity from both using the Source or Products for its own internal purposes and Conveying the Source or Products or any modifications to them to any person other than You. Any modifications made by the entity shall be deemed to be made by You pursuant to subsection 3.2.

您可以向您委托进行开发、测试或质量保证工作的法律实体传递受保护源、经修改的受保护源或产品，但该实体进行上述工作时不能将受保护源或产品用于其内部目的，并将受保护源或产品或对其进行的任何修改传递给您以外的任何人。该实体作出的任何修改应被视为由您根据第3.2款所作出。

 **6 DISCLAIMER AND LIABILITY** 

 **6 免责声明和责任** 

6.1 DISCLAIMER OF WARRANTY —The Covered Source and any Products are provided 'as is' and any express or implied warranties, including, but not limited to, implied warranties of merchantability, of satisfactory quality, non-infringement of third party rights, and fitness for a particular purpose or use are disclaimed in respect of any Source or Product to the maximum extent permitted by law. The Licensor makes no representation that any Source or Product does not or will not infringe any patent, copyright, trade secret or other proprietary right. The entire risk as to the use, quality, and performance of any Source or Product shall be with You and not the Licensor. This disclaimer of warranty is an essential part of this Licence and a condition for the grant of any rights granted under this Licence.

6.1 免责声明—受保护源和任何产品都是 "按原样 "提供的，在法律允许的最大范围内，放弃对任何源或产品的任何明示或暗示保证，包括但不限于对适销性、令人满意的质量、不侵犯第三方权利、以及对特定目的或用途的适用性的暗示保证，。许可人不对任何源或产品没有或不会侵犯任何专利、版权、商业秘密或其他专有权利作出保证。任何源或产品的使用、质量和性能相关的全部风险应由您而非许可人承担。该免责声明是本许可证的重要组成部分，也是根据本许可证授予任何权利的条件。

6.2 EXCLUSION AND LIMITATION OF LIABILITY—The Licensor shall, to the maximum extent permitted by law, have no liability for direct, indirect, special, incidental, consequential, exemplary, punitive or other damages of any character including, without limitation, procurement of substitute goods or services, loss of use, data or profits, or business interruption, however caused and on any theory of contract, warranty, tort (including negligence), product liability or otherwise, arising in any way in relation to the Covered Source, modified Covered Source and/or the Making or Conveyance of a Product, even if advised of the possibility of such damages, and You shall hold the Licensor(s) free and harmless from any liability, costs, damages, fees and expenses, including claims by third parties, in relation to such use.

6.2 责任的排除和限制—在法律允许的最大范围内，许可人不应对受保护源，经修改的受保护源、和/或产品的制造和传递相关的、以任何形式产生的直接、间接、特殊、附带、衍生、惩戒性、惩罚性或其他任何性质的损害承担任何责任，包括但不限于采购替代商品或服务，使用、数据或利润的损失，或业务中断，无论因何所致并基于合同、保证、侵权（包括过失）、产品责任或其他任何的责任理论，即使许可人被告知有发生此类损害的可能性，您也应使许可人（们）免于承担与此类使用有关的任何责任、成本、损害赔偿、费用和开支，包括第三方索赔。


 **7 Patents** 

 **7 专利** 

7.1 Subject to the terms and conditions of this Licence, each Licensor hereby grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable (except as stated in subsections 7.2 and 8.4) patent license to Make, have Made, use, offer to sell, sell, import, and otherwise transfer the Covered Source and Products, where such licence applies only to those patent claims licensable by such Licensor that are necessarily infringed by exercising rights under the Covered Source as Conveyed by that Licensor.

7.1 根据本许可证的条款和条件，各许可人特此授予您永久的、全球范围的、非独占的、免费的、免许可费的、不可撤销的（除第7.2和8.4款规定外）专利许可，用以制造、委托制造、使用、许诺销售、销售、进口和以其他方式转让受保护源和产品，该许可仅适用于该许可人专利权所覆盖的权利要求、且因行使该许可人所传递的受保护源相关的权利而必然侵犯此等专利权利要求。

7.2 If You institute patent litigation against any entity (including a cross-claim or counterclaim in a lawsuit) alleging that the Covered Source or a Product constitutes direct or contributory patent infringement, or You seek any declaration that a patent licensed to You under this Licence is invalid or unenforceable then any rights granted to You under this Licence shall terminate as of the date such process is initiated.

7.2 如果您对任何实体提起专利诉讼（包括诉讼中的交叉诉讼或反诉），指控受保护源或产品构成直接或间接的专利侵权，或者您请求宣告根据本许可证许可给您的专利是无效的或不可执行的，则本许可证给予您的任何授权应在此类程序启动之日起终止。

 **8 General** 

 **8 一般条款** 

8.1 If any provisions of this Licence are or subsequently become invalid or unenforceable for any reason, the remaining provisions shall remain effective.

8.1 如果本许可证的任何条款因任何原因而无效或无法执行，或随后如此，其余条款仍应有效。

8.2 You shall not use any of the name (including acronyms and abbreviations), image, or logo by which the Licensor or CERN is known, except where needed to comply with section 3, or where the use is otherwise allowed by law. Any such permitted use shall be factual and shall not be made so as to suggest any kind of endorsement or implication of involvement by the Licensor or its personnel.

8.2 您不得使用许可人或CERN为人所知的任何名称（包括首字母缩写）、图像或标识，除非为了遵守第3款的规定，或法律允许此类使用。任何允许的此类使用应是事实性的，且不应暗示许可人或其员工作出任何形式的认可或暗示其参与。

8.3 CERN may publish updated versions and variants of this Licence which it considers to be in the spirit of this version, but may differ in detail to address new problems or concerns. New versions will be published with a unique version number and a variant identifier specifying the variant. If the Licensor has specified that a given variant applies to the Covered Source without specifying a version, You may treat that Covered Source as being released under any version of the CERN-OHL with that variant. If no variant is specified, the Covered Source shall be treated as being released under CERN-OHL-S. The Licensor may also specify that the Covered Source is subject to a specific version of the CERN-OHL or any later version in which case You may apply this or any later version of CERN-OHL with the same variant identifier published by CERN.

8.3 CERN可以发布其认为符合本版本许可证精神的更新版许可证和变体，但可能在细节上有所不同，以解决新问题或担忧。新版本在发布时将公布一个独特的版本号和一个指明变体的变体标识符。如果许可人指明某一变体适用于受保护源，但未指明版本，则您可以将该受保护源视为根据具有该变体的CERN-OHL的任何版本发布。如果没有指名变体，受保护源应被视为根据CERN-OHL-S发布。许可人还可以指明受保护源应遵循CERN-OHL的特定版本或任何后续版本，在此情况下，您可以适用此版本或任何后续版本的CERN-OHL，并附以CERN发布的相同变体标识。

8.4 This Licence shall terminate with immediate effect if You fail to comply with any of its terms and conditions.

8.4 如果您未能遵守本许可证的任何条款和条件，本许可证应立即终止。

8.5 However, if You cease all breaches of this Licence, then Your Licence from any Licensor is reinstated unless such Licensor has terminated this Licence by giving You, while You remain in breach, a notice specifying the breach and requiring You to cure it within 30 days, and You have failed to come into compliance in all material respects by the end of the 30 day period. Should You repeat the breach after receipt of a cure notice and subsequent reinstatement, this Licence will terminate immediately and permanently. Section 6 shall continue to apply after any termination.

8.5 然而，如果您停止所有违反本许可证的行为，则您将恢复从任何许可人处获得的许可，除非该许可人在您违反本许可证期间向您发出声明违反行为的通知，并要求您在30天内纠正此行为，而您在30天期限结束时未能在所有实质性方面符合本许可证要求。如果您在收到纠正通知且随后恢复许可后再次违反本许可证，则本许可证将立即永久性终止。第6款在任何终止后仍应继续适用。

8.6 This Licence shall not be enforceable except by a Licensor acting as such, and third party beneficiary rights are specifically excluded.

8.6 除非许可人按照本许可证行事，且明确排除第三方受益人权利，否则本许可证不得执行。




