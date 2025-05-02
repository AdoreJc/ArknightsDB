# UniEquipInfoDetailTalentContentGroup

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Transform _talentContainer`

- `GameObject _contentItemPrefab`


## Methods

- `Void Render(CharacterTalentViewModel[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipInfoDetailTalentContentGroup : MonoBehaviour, IHotfixable
{
	private Transform _talentContainer; // 0x18
	private GameObject _contentItemPrefab; // 0x20
	private CharacterTalentViewModel[] m_talentsCache; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x22ff790 VA: 0x7594917790
	public Void Render(CharacterTalentViewModel[] talents) { }
	// RVA: 0x22ff988 VA: 0x7594917988
	public Void .ctor() { }
}
```