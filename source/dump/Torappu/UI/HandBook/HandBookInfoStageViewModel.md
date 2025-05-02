# HandBookInfoStageViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookStageViewModel handbookViewModel`

- `SkillGroupViewModel skillGroupModel`

- `Int32 selectIdx`

- `Sprite logoSprite`


## Methods

- `Void LoadData(Params)`

- `Void LoadDataByJumpParam(HandBookJumpParam)`

- `Void _LoadCharData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStageViewModel : IHotfixable
{
	public HandBookStageViewModel handbookViewModel; // 0x10
	public SkillGroupViewModel skillGroupModel; // 0x18
	public List`1 charList; // 0x20
	public Int32 selectIdx; // 0x28
	public Sprite logoSprite; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_LoadDataByJumpParam; // 0x8
	private static DelegateBridge __Hotfix0__LoadCharData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ea14a8 VA: 0x75954b94a8
	public Void LoadData(Params param) { }
	// RVA: 0x2ea16cc VA: 0x75954b96cc
	public Void LoadDataByJumpParam(HandBookJumpParam jumpParam) { }
	// RVA: 0x2ea1578 VA: 0x75954b9578
	private Void _LoadCharData(String charId) { }
	// RVA: 0x2ea1860 VA: 0x75954b9860
	public Void .ctor() { }
}
```