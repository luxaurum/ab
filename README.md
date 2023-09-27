# b
<mxfile host="65bd71144e">
    <diagram id="3e-c7wMI18iRUAbZvPqD" name="Page-1">
        <mxGraphModel dx="1440" dy="1080" grid="0" gridSize="1" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
            <root>
                <mxCell id="0"/>
                <mxCell id="1" parent="0"/>
                <mxCell id="2" value="Follower" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
                    <mxGeometry x="220" y="25" width="140" height="90" as="geometry"/>
                </mxCell>
                <mxCell id="3" value="Readers" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="2">
                    <mxGeometry y="30" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="4" value="interested Readers" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="2">
                    <mxGeometry y="60" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="32" style="edgeStyle=none;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.484;entryY=1.093;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=ERmany;endFill=0;startArrow=ERone;startFill=0;" edge="1" parent="1" source="6" target="4">
                    <mxGeometry relative="1" as="geometry"/>
                </mxCell>
                <mxCell id="6" value="Author" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
                    <mxGeometry x="220" y="195" width="140" height="90" as="geometry"/>
                </mxCell>
                <mxCell id="7" value="&lt;span&gt;Walter&lt;br&gt;Isaacson's bio&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="6">
                    <mxGeometry y="30" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="8" value="&lt;span style=&quot;font-family: Calibri, sans-serif; font-size: 14.6667px;&quot;&gt;book count&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="6">
                    <mxGeometry y="60" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="33" style="edgeStyle=none;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.5;entryY=1.122;entryDx=0;entryDy=0;entryPerimeter=0;startArrow=ERmany;startFill=0;endArrow=ERmany;endFill=0;" edge="1" parent="1" source="10" target="8">
                    <mxGeometry relative="1" as="geometry"/>
                </mxCell>
                <mxCell id="10" value="Reviewer" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
                    <mxGeometry x="220" y="350" width="140" height="120" as="geometry"/>
                </mxCell>
                <mxCell id="11" value="&lt;span style=&quot;font-size:11.0pt;line-height:107%;&lt;br/&gt;font-family:&amp;quot;Calibri&amp;quot;,sans-serif;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:&lt;br/&gt;Calibri;mso-fareast-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;&lt;br/&gt;mso-bidi-font-family:&amp;quot;Times New Roman&amp;quot;;mso-bidi-theme-font:minor-bidi;&lt;br/&gt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA&quot;&gt;Coulson&lt;br/&gt;Liu&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="10">
                    <mxGeometry y="30" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="12" value="&lt;span style=&quot;font-size:11.0pt;line-height:107%;&lt;br/&gt;font-family:&amp;quot;Calibri&amp;quot;,sans-serif;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:&lt;br/&gt;Calibri;mso-fareast-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;&lt;br/&gt;mso-bidi-font-family:&amp;quot;Times New Roman&amp;quot;;mso-bidi-theme-font:minor-bidi;&lt;br/&gt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA&quot;&gt;Marcus&lt;br/&gt;Aurelius&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="10">
                    <mxGeometry y="60" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="13" value="etc.." style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="10">
                    <mxGeometry y="90" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="38" style="edgeStyle=none;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;startArrow=ERmany;startFill=0;endArrow=ERmany;endFill=0;entryX=0.5;entryY=1.111;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="14" target="22">
                    <mxGeometry relative="1" as="geometry">
                        <mxPoint x="560" y="140" as="targetPoint"/>
                    </mxGeometry>
                </mxCell>
                <mxCell id="14" value="Book" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
                    <mxGeometry x="490" y="180" width="140" height="120" as="geometry"/>
                </mxCell>
                <mxCell id="15" value="&lt;span&gt;Title:Elon Musk&lt;br&gt;Book Cover&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="14">
                    <mxGeometry y="30" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="16" value="&#10;&lt;span style=&quot;color: rgb(240, 240, 240); font-family: Helvetica; font-size: 12px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(42, 37, 47); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;&quot;&gt;Pages&lt;/span&gt;&#10;&#10;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="14">
                    <mxGeometry y="60" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="17" value="&lt;span style=&quot;font-family: Calibri, sans-serif; font-size: 14.6667px;&quot;&gt;Publication Date&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="14">
                    <mxGeometry y="90" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="19" value="Genre" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
                    <mxGeometry x="490" y="10" width="140" height="120" as="geometry"/>
                </mxCell>
                <mxCell id="20" value="&lt;span&gt;Biography&lt;br&gt;&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="19">
                    <mxGeometry y="30" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="21" value="Nonfiction" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="19">
                    <mxGeometry y="60" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="22" value="&lt;span style=&quot;font-family: Calibri, sans-serif; font-size: 14.6667px;&quot;&gt;Business&lt;/span&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="19">
                    <mxGeometry y="90" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="36" style="edgeStyle=none;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.5;entryY=1.111;entryDx=0;entryDy=0;entryPerimeter=0;startArrow=ERmany;startFill=0;endArrow=ERone;endFill=0;" edge="1" parent="1" source="23" target="17">
                    <mxGeometry relative="1" as="geometry"/>
                </mxCell>
                <mxCell id="23" value="Review Rating" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
                    <mxGeometry x="490" y="350" width="140" height="120" as="geometry"/>
                </mxCell>
                <mxCell id="24" value="Book Rating" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="23">
                    <mxGeometry y="30" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="25" value="No of Rating" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="23">
                    <mxGeometry y="60" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="26" value="Book Review" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;rotatable=0;whiteSpace=wrap;html=1;" vertex="1" parent="23">
                    <mxGeometry y="90" width="140" height="30" as="geometry"/>
                </mxCell>
                <mxCell id="35" style="edgeStyle=none;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.5;entryY=1;entryDx=0;entryDy=0;entryPerimeter=0;startArrow=ERone;startFill=0;endArrow=ERmany;endFill=0;" edge="1" parent="1" source="31" target="26">
                    <mxGeometry relative="1" as="geometry"/>
                </mxCell>
                <mxCell id="31" value="Community Rating" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
                    <mxGeometry x="500" y="530" width="120" height="60" as="geometry"/>
                </mxCell>
                <mxCell id="34" style="edgeStyle=none;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;startArrow=ERone;startFill=0;endArrow=ERmany;endFill=0;" edge="1" parent="1" source="12" target="25">
                    <mxGeometry relative="1" as="geometry"/>
                </mxCell>
                <mxCell id="37" style="edgeStyle=none;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;startArrow=ERmany;startFill=0;endArrow=ERone;endFill=0;" edge="1" parent="1" source="16" target="8">
                    <mxGeometry relative="1" as="geometry"/>
                </mxCell>
            </root>
        </mxGraphModel>
    </diagram>
</mxfile>
