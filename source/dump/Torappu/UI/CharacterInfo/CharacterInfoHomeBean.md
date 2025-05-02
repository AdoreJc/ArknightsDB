# CharacterInfoHomeBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterProfileViewProperty profileProperty`

- `AttributeViewProperty attributeProperty`

- `SkillGroupViewProperty skillProperty`

- `BattleInfoViewProperty battleProperty`

- `CharacterIllustViewProperty illustProperty`

- `BoolProperty isCharacterLocked`

- `Int32 charInstId`

- `String charId`

- `Boolean isReachMaxEvolve`


## Methods

- `Void LoadData(Int32)`

- `Void ClearData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoHomeBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public CharacterProfileViewProperty profileProperty; // 0x18
	public AttributeViewProperty attributeProperty; // 0x20
	public SkillGroupViewProperty skillProperty; // 0x28
	public BattleInfoViewProperty battleProperty; // 0x30
	public CharacterIllustViewProperty illustProperty; // 0x38
	public BoolProperty isCharacterLocked; // 0x40
	public Int32 charInstId; // 0x48
	public String charId; // 0x50
	public Boolean isReachMaxEvolve; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_ClearData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d56fc8 VA: 0x759536efc8
	public Void LoadData(Int32 charInstIdParam) { }
	// RVA: 0x2d574c0 VA: 0x759536f4c0
	public Void ClearData() { }
	// RVA: 0x2d57578 VA: 0x759536f578
	public Void .ctor() { }
}
```