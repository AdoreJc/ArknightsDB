# CharacterInfoDetailTalentContentGroup

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Transform _talentContainer`

- `GameObject _contentItemPrefab`


## Methods

- `Void Render(CharacterTalentViewModel[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoDetailTalentContentGroup : MonoBehaviour, IHotfixable
{
	private Transform _talentContainer; // 0x18
	private GameObject _contentItemPrefab; // 0x20
	private CharacterTalentViewModel[] m_talentsCache; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d8cbe4 VA: 0x75953a4be4
	public Void Render(CharacterTalentViewModel[] talents) { }
	// RVA: 0x2d8cf58 VA: 0x75953a4f58
	public Void .ctor() { }
}
```