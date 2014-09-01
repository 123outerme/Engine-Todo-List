DelVar CDelVar BDelVar Q
"ABCDEFGHIJKLMNOPQRSTUVWXYZ 1234567890→Str1
SetUpEditor ʟENSAV
FnOff :GridOff:AxesOff:PlotsOff 
If not(dim(ʟENSAV:{10,0,1,0,0→ʟENSAV
SetUpEditor ʟA,ʟB,ʟC,ʟD,ʟE,ʟF
If not(dim(ʟA:{27,27→ʟA
If not(dim(ʟB:{27,27→ʟB
If not(dim(ʟC:{27,27→ʟC
If not(dim(ʟD:{27,27→ʟD
If not(dim(ʟE:{27,27→ʟE
If not(dim(ʟF:{27,27→ʟF
0→Xmin:Ans→Ymin
94→Xmax:62→Ymax
If ʟENSAV(3)=1:":→Str4
If ʟENSAV(3)=2:">→Str4
If ʟENSAV(3)=3:"π→Str4
Lbl 2:" →Str2
Ans→Str3
Ans→Str5
Ans→Str6
Ans→Str7
Ans→Str8
ClrHome
Output(1,1,"MODE=MENU
Output(2,1,"----------------
For(X,1,dim(ʟA
ʟA(X)→B
sub(Str1,B,1
Str2+Ans→Str2
Output(3,1,Str2:End
For(X,1,dim(ʟB
ʟB(X)→B
sub(Str1,B,1
Str3+Ans→Str3
Output(4,1,Str3:End
For(X,1,dim(ʟC
ʟC(X)→B
sub(Str1,B,1
Str5+Ans→Str5
Output(5,1,Str5:End
For(X,1,dim(ʟD
ʟD(X)→B
sub(Str1,B,1
Str6+Ans→Str6
Output(6,1,Str6:End
For(X,1,dim(ʟE
ʟE(X)→B
sub(Str1,B,1
Str7+Ans→Str7
Output(7,1,Str7:End
For(X,1,dim(ʟF
ʟF(X)→B
sub(Str1,B,1
Str8+Ans→Str8:End
DelVar L
Lbl 1
DelVar C3→A
Output(A,1,Str4
Repeat B:getKey→B
If B=105:Then:DelVar LClrHome:Output(1,1,"SAVING...
Goto 7:End
If B=25 and A≥4:2→C
If B=34 and A<8:1→C
If B=31:Then:Lbl J:ClrHome:Input Str0
If length(Str0)>14:Then:Output(1,1,"ERR 1:
Output(2,1,"TOO LONG
Pause :ClrHome:Goto K:End
" "+Str0→Str0
DelVar B1→Q:Goto 7:End
If B=21 and dim(ʟA>1:Then:Output(A,2,"                
If A=3:Goto A
If A=4 and dim(ʟB>1:Goto B
If A=5 and dim(ʟC>1:Goto C
If A=6 and dim(ʟD>1:Goto D
If A=7 and dim(ʟE>1:Goto E
If A=8 and dim(ʟF>1:Goto F
Lbl A:Str3→Str2
Lbl B:Str5→Str3
Lbl C:Str6→Str5
Lbl D:Str6→Str7
Lbl E:Str7→Str8
Lbl F:" →Str8
ʟENSAV(1)+2→ʟENSAV(1)
DelVar Q1→F:Ans→L:Goto 7:End
If B=22:Then:Goto 5:End
If B:Output(A,1," 
If C=1:A+1→A
If C=2:A-1→A
Output(A,1,Str4
DelVar CDelVar BDelVar L:End
Lbl 6
If Q:Then:Str7→Str8
Str6→Str7:Str5→Str6
Str3→Str5:Str2→Str3
Str0→Str2:DelVar Str0DelVar Q1→L:End
DelVar ʟADelVar ʟBDelVar ʟCDelVar ʟDDelVar ʟEDelVar ʟF
For(C,1,length(Str2
inString(Str1,sub(Str2,C,1→ʟA(C
End
For(C,1,length(Str3
inString(Str1,sub(Str3,C,1→ʟB(C
End
For(C,1,length(Str5
inString(Str1,sub(Str5,C,1→ʟC(C
End
For(C,1,length(Str6
inString(Str1,sub(Str6,C,1→ʟD(C
End
For(C,1,length(Str7
inString(Str1,sub(Str7,C,1→ʟE(C
End
For(C,1,length(Str8
inString(Str1,sub(Str8,C,1→ʟF(C
End
If dim(ʟA)=1:{27,27→ʟA
If dim(ʟB)=1:{27,27→ʟB
If dim(ʟC)=1:{27,27→ʟC
If dim(ʟD)=1:{27,27→ʟD
If dim(ʟE)=1:{27,27→ʟE
If dim(ʟF)=1:{27,27→ʟF
DeltaList(cumSum(ʟA→ʟA
DeltaList(cumSum(ʟB→ʟB
DeltaList(cumSum(ʟC→ʟC
DeltaList(cumSum(ʟD→ʟD
DeltaList(cumSum(ʟE→ʟE
DeltaList(cumSum(ʟF→ʟF
If not(L:Then:DelVar Str1DelVar Str2DelVar Str3DelVar Str4DelVar Str5DelVar Str6DelVar Str7DelVar Str8DelVar ADelVar BDelVar CDelVar DDelVar EDelVar FDelVar GDelVar HDelVar IDelVar JDelVar KDelVar LDelVar MDelVar NDelVar ODelVar PDelVar QDelVar RDelVar SDelVar TDelVar UDelVar VDelVar WDelVar XDelVar YDelVar ZDelVar θSetUpEditor ʟA,ʟB,ʟC,ʟD,ʟE,ʟF,ʟENSAV:ClrHome
Return:Else:3→A:Goto 8:End
Lbl 8:End:Goto 2
Lbl 9:End:Goto 1
Lbl K:End:Goto J
Lbl 7:End:Goto 6
Lbl N:End:Goto I
Lbl P:End:Goto Q
Lbl 5:End:DelVar BClrDraw
Text(0,1,"MENU
Text(12,1,"1. MOTOR SHOP
Text(24,1,"2. GAMES
Text(36,1,"3. OPTIONS
Text(48,1,"4. EXIT
Repeat B=92 or B=93 or B=94 or B=82
getKey→B:End
If Ans=82:Then:Goto 8:End
If B=94:Then:Goto H:End
If B=92:Then:Lbl O:DelVar CDelVar BʟENSAV(1)→S
ClrDraw
Text(0,1,"SPARKS:
Text(12,1,S
Pause :ClrDraw
Text(0,1,"*MOTOR SHOP*/DEL=BACK
Text(12,1,"1. > CURSOR (20)
Text(24,1,"2. π CURSOR (60)
Text(36,1,"3. MINIGAME 1 (80)
Text(48,1,"4. MINIGAME 2 (100)
Repeat B
getKey→B
If Ans=92:4→C
If B=93:5→C
If B=94:6→C
If B=82:7→C
If B=23:Goto 5
If C:Goto 0
DelVar B:End
Lbl 0
If C=4 and S≥20:Then
S-20→ʟENSAV(1)
2→ʟENSAV(3)
1→ʟENSAV(4)
ClrDraw
Text(0,1,"PURCHASED!
End
If C=5 and S≥60:Then
S-60→ʟENSAV(1)
3→ʟENSAV(3)
1→ʟENSAV(5)
ClrDraw
Text(0,1,"PURCHASED!
End
If C=6 and S≥80:Then
S-80→ʟENSAV(1)
1+ʟENSAV(2)→ʟENSAV(2)
End
If C=7 and S≥100:Then
S-100→ʟENSAV(1)
2+ʟENSAV(2)→ʟENSAV(2)
ClrDraw
Text(0,1,"PURCHASED!
End
DelVar S
If C:Goto O
End
If B=93:Then:DelVar BClrDraw:Lbl I
Text(0,1,"+MINGAMES+
ʟENSAV(3)→S:If Ans=1 or Ans=3:Text(12,1,"1. MINIGAME 1
If S≥2:Text(24,1,"2. MINIGAME 2
DelVar SText(36,1,"3. BACK
Repeat B
getKey→B
If Ans=94:Then:Goto 5:End
If B=93 and ʟENSAV(3)≥2:Then:Goto M:End
If B=92 and (ʟENSAV(3)=1 or ʟENSAV(3)=3:Then:Lbl Q:DelVar KDelVar TClrHome
Output(1,1,"<+> TO MOVE.
Output(2,1,"2ND TO QUIT.
Pause :ClrHome
4→W:Ans→V
1→I:Ans→U
Repeat K=21:getKey→K
If Ans:Output(8,W," 
Output(U,V," 
min(16,max(1,W+sum(DeltaList(Ans={24,26→W
1+U→U
Output(8,W,"W
Output(U,V,"I
If U=8 and V=W:Then:Output(1,1,"GAME OVER!
Output(2,1,"SCORE:
Output(2,7,T
If T≥50:Output(3,1,"WON SPARKS!
Pause :ClrHome:21→K
Menu("AGAIN?","YES",P,"NO",N
End
If int(T/75≥1:10+ʟENSAV(1)→ʟENSAV(1)
If U=8:Then:Output(8,V," 
1→U:W→V:1+T→T:End
End
ClrHome:DelVar BDelVar UDelVar VDelVar WDelVar T:Goto I
End
Lbl M:End
ClrHome
DelVar TDelVar QOutput(1,1,"<+> TO MOVE.
Output(2,1,"2ND TO QUIT. 
Output(3,1,"COS TO SHOOT.
Pause :ClrHome
4→W:Ans→V
1→S:Ans→U
Repeat K=21:getKey→K
If Ans:Output(8,W," 
If S=U:Output(U,V," 
min(16,max(1,W+sum(DeltaList(Ans={24,26→W
.25+S→S
int(S→U
Output(8,W,"θ
Output(U,V,"Y
If U≠1:Output(U-1,V," 
If U=8:Then:Output(1,1,"GAME OVER!
Output(2,1,"SCORE:
Output(2,7,T
If T≥10:Output(3,1,"WON SPARKS!
Pause :ClrHome
21→K
Menu("AGAIN?","YES",M,"NO",N
End
If K=53:Then:For(Q,1,7:8-Q:Output(Ans,W,".
Output(Ans+1,W," 
End:1→Q:Output(1,W," 
If W=V and Q:Then:Output(U,V," 
1→U:randInt(1,6)→V:DelVar Q1+T→T:If S≥2:S-1→S:End
End
If int(T/10≥1:Then:20+ʟENSAV(1)→ʟENSAV(1)
End:End
DelVar TDelVar UDelVar VDelVar WDelVar S:If 1:Then
End
End
Goto I
Lbl H:End:DelVar BClrDraw
Text(0,1,"OPTIONS:
Text(12,1,"1. SETTINGS
Text(24,1,"2. HELP
Text(36,1,"3. BACK
Repeat B:getKey→B:End
If Ans=94:Then:Goto 5:End
If B=93:Then:Goto G:End
If B=92:Then:DelVar BClrDraw:Goto L:End
End
Lbl L:End
Text(0,1,"SETTINGS:
Text(12,1,"1. : CURSOR
If ʟENSAV(4):Text(24,1,"2. > CURSOR
If ʟENSAV(5):Text(36,1,"3. π CURSOR
Text(48,1,"4. BACK
Repeat B:getKey→B
If Ans=82:Then:DelVar BClrDraw:Goto H:End
If B=92:Then:1→ʟENSAV(2):ClrDraw:Text(0,1,"SAVED!
Pause :ClrDraw:Goto L:End
If B=93 and ʟENSAV(4):Then:">→Str2:2→ʟENSAV(2):ClrDraw:Text(0,1,"SAVED!
Pause :ClrDraw:Goto L:End
If B=94 and ʟENSAV(5):Then:"π→Str2:3→ʟENSAV(2):ClrDraw:Text(0,1,"SAVED!
Pause :ClrDraw:Goto L:End
End
Lbl G:End:ClrDraw
Text(0,1,"ENTER TO QUIT, 2ND TO
Text(12,1,"CHECK OFF AN ENTRY,
Text(24,1,"ALPHA TO ADD A NEW 
Text(36,1,"ENTRY. ENTER TO
Text(48,1,"SAVE AND QUIT.
Pause :ClrDraw
Text(0,1,"A TILDA^3 PROD.
Text(12,1,"CODED BY 123OUTERME.
Text(24,1,"V1.2.5
Pause :DelVar BClrDraw
If B=93:Then:Goto H:End
