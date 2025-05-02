# BattleReplaySettings

**Namespace:** `Torappu.Battle.DevelopTools.Tester`


## Fields

- `TextAsset _runeTableJson`


## Methods

- `Boolean TryGetBattlelog(String, out)`

- `Boolean TryGetRuneList(BattleLog, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.DevelopTools.Tester
public class BattleReplaySettings : MonoBehaviour
{
	private TextAsset _runeTableJson; // 0x18


	// RVA: 0x1d2d164 VA: 0x7594345164
	public Boolean TryGetBattlelog(String replayFile, out BattleLog battleLog) { }
	// RVA: 0x1d2d1cc VA: 0x75943451cc
	public List`1 ConvertToCharacterInst(BattleLog battleLog, out AdvancedCharacterInst assistChar) { }
	// RVA: 0x1d2d4d4 VA: 0x75943454d4
	public List`1 ConvertToCharacterInst(Journal journal, out AdvancedCharacterInst assistChar) { }
	// RVA: 0x1d2d218 VA: 0x7594345218
	private List`1 _DoConvertToCharacterInst(Journal journal, out AdvancedCharacterInst assistChar) { }
	// RVA: 0x1d2d6a0 VA: 0x75943456a0
	public Boolean TryGetRuneList(BattleLog battleLog, out List`1 runeList) { }
	// RVA: 0x1d2d504 VA: 0x7594345504
	private static String _GetCharIdFromPossbileSkinId(String skinOrCharId, String tmplId) { }
	// RVA: 0x1d2d99c VA: 0x759434599c
	public Void .ctor() { }
}
```