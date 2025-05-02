# CharacterInfoEvolveStateBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Int32 chrInstId`

- `String chrRealName`

- `String charId`

- `String tmplId`

- `EvolveAttributeViewModel evolveAttrs`

- `String oldIllustId`

- `CharUISkinStruct oldSkinStruct`

- `String newIllustId`

- `CharUISkinStruct newSkinStruct`

- `Boolean afterEvolveFlag`

- `EvolvePhase evolvePhase`

- `PlayerCharacter cachePlayerData`

- `CharacterInfoEvolveInfoViewModel evolveInfoViewModel`


## Methods

- `Void LoadData(Int32)`

- `Boolean IsAllRequiresSatisfied()`

- `String CheckEvolveRequirements()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoEvolveStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public Int32 chrInstId; // 0x18
	public String chrRealName; // 0x20
	public String charId; // 0x28
	public String tmplId; // 0x30
	public EvolveAttributeViewModel evolveAttrs; // 0x38
	public RequireViewModel[] evolveRequires; // 0x40
	public String oldIllustId; // 0x48
	public CharUISkinStruct oldSkinStruct; // 0x50
	public String newIllustId; // 0x60
	public CharUISkinStruct newSkinStruct; // 0x68
	public Boolean afterEvolveFlag; // 0x78
	public EvolvePhase evolvePhase; // 0x7c
	public PlayerCharacter cachePlayerData; // 0x80
	public CharacterInfoEvolveInfoViewModel evolveInfoViewModel; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__ParseEvolveRequirements; // 0x8
	private static DelegateBridge __Hotfix0_IsAllRequiresSatisfied; // 0x10
	private static DelegateBridge __Hotfix0_CheckEvolveRequirements; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d59c30 VA: 0x7595371c30
	public Void LoadData(Int32 charInstId) { }
	// RVA: 0x2d5a0fc VA: 0x75953720fc
	private static RequireViewModel[] _ParseEvolveRequirements(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x2d5a854 VA: 0x7595372854
	public Boolean IsAllRequiresSatisfied() { }
	// RVA: 0x2d5a984 VA: 0x7595372984
	public String CheckEvolveRequirements() { }
	// RVA: 0x2d5afc4 VA: 0x7595372fc4
	public Void .ctor() { }
}
```