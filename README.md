# ReverseName

string name = "Payal";
char[] chArray = name.ToCharArray();
string reverseName = "";
for(int i = chArray.Length-1;i >-1 ; i--){
	reverseName = reverseName + chArray[i];
}
