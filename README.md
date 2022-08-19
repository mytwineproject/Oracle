<?xml version="1.0" encoding="utf-8"?>
<html xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
    <head>
        <meta name="description" content="Learn how to create message variants." />
        <meta name="keywords" content="create message variants, creating message variants, message, messages, variant, variants" />
    </head>
    <body>
        <h1>Creating message variants</h1>
        <p>Variants can be created for subject lines and for  regions in your email message to personalize your email content. You can create up to 50 variants per region.  Variants can be created using the source editor and the visual editor.</p>
        <p class="task_intro">To create message variants:</p>
        <ol>
            <li>After creating your message based on the steps listed in <MadCap:xref href="CreatingMessages.htm">Creating messages</MadCap:xref>, select the subject line or region of your message for which you want to create a variant. </li>
            <p class="note"><b>Note</b>: When using the source editor, you can only create variants for regions that have <code>&lt;td&gt;</code> or <code>&lt;div&gt;</code> tags, and when using the visual editor, you can only create variants for regions that are layouts.</p>
            <li>
                <p>Select <img src="../../Resources/Images/Messages/VariantsIcon.png" alt="Image of the variants icon to select when creating a variant." class="icon_Inline_XSmall_NoAction" /><b>Variants</b>.</p>
            </li>
            <li>
                <p>Click <b>Create Variant</b>.</p>
            </li>
            <li>In the variant design editor for your variant, name your variant in the Variant Name box. By default, your variant is given the name Default Variant Name.</li>
            <p>
                <img src="../../Resources/Images/Messages/VariantPage.png" alt="An image showing where to insert the name for a variant on the variant page display." class="screenshot_Large_Popup" />
            </p>
            <li>
                <p>In the <b>Who will see this variant?</b> tab, decide who will see the variant based on contact attributes. To define a condition, drag attributes from the right panel to the  canvas. Fill in the conditional fields and operators for each condition to define the conditions within the groups.</p>
            </li>
            <p class="tip"><b>Tip</b>: You can edit the page so that contacts who either meet any or all conditions can see the variant. When defining who will see this variant, you can create up to 10 conditions per condition group, and up to 30 condition groups per variant. </p>
            <p>The following video clip demonstrates steps 1 to 5:</p>
            <p>
                <div class="videoWrapper"><iframe id="kaltura_player" width="560" height="315" src="https://cdnapisec.kaltura.com/p/2171811/sp/217181100/embedIframeJs/uiconf_id/35965902/partner_id/2171811?iframeembed=true&amp;playerId=kaltura_player&amp;entry_id=1_1x0dhv3c" frameborder="0" allowfullscreen="1"></iframe>
                </div>
            </p>
            <p>&#160;</p>
            <li>
                <p>Click the <b>What will they see?</b> tab to customize what the contacts will see if they meet your conditions. In the source editor, you can choose to add a single image, add content using an HTML or a WYSIWYG editor, or you can choose to display no content. In the visual editor, you can either display no content or add a single layout to customize your variant.</p>
            </li>
            <li>
                <p>Click <b>Done</b>. You will be taken back to the <b>Variants</b> tab. To view your variant, choose it from the list of variants.</p>
            </li>
            <li>Click <b>Save</b>.</li>
            <p>The following video clip demonstrates steps 6 to 8:</p>
            <p>
                <div class="videoWrapper"><iframe id="kaltura_player" width="560" height="315" src="https://cdnapisec.kaltura.com/p/2171811/sp/217181100/embedIframeJs/uiconf_id/35965902/partner_id/2171811?iframeembed=true&amp;playerId=kaltura_player&amp;entry_id=1_dp28vrs9" frameborder="0" allowfullscreen="1"></iframe>
                </div>
            </p>
            <div class="important"><b>Important</b>:<ul><li><p>A contact will receive the content from the first variant for which they meet the conditions. Ensure that you organize your variants in the order you want them evaluated. To change the order of the variants, use the <img src="../../Resources/Images/Messages/MoreActions.png" alt="An image of the more actions icon." class="icon_Inline_XSmall_NoAction" /> menu and choose <b>Move up</b> or <b>Move down</b>. If the contact meets none of the variant conditions, the <b>Default</b> variant will display.</p></li><li MadCap:conditions="ContentStatus.Draft"><p><MadCap:annotation MadCap:createDate="2022-05-05T23:57:44.9595088-07:00" MadCap:creator="jmpohl" MadCap:initials="JM" MadCap:comment="Modified for 22B" MadCap:editor="jmpohl" MadCap:editDate="2022-05-05T23:57:48.4077873-07:00">With the 22B update, all attributes you used in the <b>Who will see this variant?</b> conditions are automatically added as data sources for the message</MadCap:annotation>. (To be added in new topic).</p></li><li><p>Contacts are skipped if they have no value for the attributes used in the variant conditions. For more information, see <MadCap:xref href="PreviewingMessageVariants.htm">Previewing message variants</MadCap:xref>.</p></li></ul></div>
        </ol>
        <p class="task_intro" style="font-weight: normal;" MadCap:conditions="ContentStatus.Draft"><b><MadCap:annotation MadCap:createDate="2022-05-05T23:57:58.4352124-07:00" MadCap:creator="jmpohl" MadCap:initials="JM" MadCap:comment="Modified procedure for 22B to be viewing the attributes added automaticallyl, and optionally changing the default variables." MadCap:editor="jmpohl" MadCap:editDate="2022-05-05T23:59:08.0329388-07:00">To view attributes used as data sources</MadCap:annotation></b>:</p>
        <ol MadCap:conditions="ContentStatus.Draft">
            <li>
                <p>Click the <b>Code</b> tab.</p>
            </li>
            <li>
                <p>Click the <b>Personalization </b> <img src="../../Resources/Images/Messages/PersonalizationToken.PNG" alt="An image of the Personalization button." class="icon_Inline_XSmall_NoAction" /> button.</p>
            </li>
            <li>
                <p>Click the <b>Manage Attributes</b> button. </p>
                <p>On the <em>Manage Attributes</em> panel, you will see the attributes you used in the <b>Who will see this?</b> conditions.</p>
                <p>
                    <img src="../../Resources/Images/Campaigns/ManageAttributesButton.png" class="screenshot_Large_Popup" alt="An image pointing to the Manage Attributes button." />
                </p>
            </li>
            <li>
                <p>Optionally, you can set a default value for the attribute. Double click the attribute’s row in the <b>Alternate Attribute Value</b> column, and a text entry field will display. Type your value in the field.</p>
                <p>
                    <img src="../../Resources/Images/Messages/ManageAttributesCanvas.png" class="screenshot_Large_Popup" alt="An image of Manage Attributes canvas." />
                </p>
            </li>
            <li>
                <p>Click <b>Done</b> when you have finished viewing attributes.</p>
            </li>
            <li>
                <p>If you added default values for any of the attributes, click <b>Save</b>.</p>
            </li>
        </ol>
        <h1 class="keywordsHidden" MadCap:autonum="">create message variants, creating message variants, message, messages, variant, variants</h1>
        <h2 MadCap:conditions="Medium.WebOnly"><MadCap:variable name="Global-TemplateVariables.Tasks" />
        </h2>
        <p MadCap:conditions="Medium.WebOnly">
            <MadCap:xref href="PreviewingMessageVariants.htm">Previewing message variants</MadCap:xref>
        </p>
        <p MadCap:conditions="Medium.WebOnly">
            <MadCap:xref href="ManagingMessageVariants.htm">Managing message variants</MadCap:xref>
        </p>
        <h2 MadCap:conditions="Medium.WebOnly"><MadCap:variable name="Global-TemplateVariables.Related" />
        </h2>
        <p>
            <MadCap:xref href="MessageVariants.htm">Message variants</MadCap:xref>
        </p>
    </body>
</html>
