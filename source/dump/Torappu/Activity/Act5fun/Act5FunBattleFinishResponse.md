# Act5FunBattleFinishResponse

**Namespace:** `Torappu.Activity.Act5fun`


## Fields

- `Int32 result`

- `Int32 score`

- `Boolean isHighScore`

- `Act5FunBattleFinishPlayerResult playerResult`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5fun
public class Act5FunBattleFinishResponse : DefaultFinishBattleResponse
{
	public Int32 result; // 0xa0
	public Int32 score; // 0xa4
	public Boolean isHighScore; // 0xa8
	public Dictionary`2 npcResult; // 0xb0
	public Act5FunBattleFinishPlayerResult playerResult; // 0xb8
	public List`1 reward; // 0xc0


	// RVA: 0x31b8b88 VA: 0x75957d0b88
	public Void .ctor() { }
}
```