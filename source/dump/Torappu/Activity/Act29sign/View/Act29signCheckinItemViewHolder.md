# Act29signCheckinItemViewHolder

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `Transform _container`

- `ActivityCommonCheckinV2Item _normalItemPrefab`

- `Act29signSpecialCheckinItem _specialItemPrefab`

- `ActivityCommonCheckinV2Item m_normalItem`

- `Act29signSpecialCheckinItem m_specialItem`


## Methods

- `Void Render(Act29signSpecialCheckinItemViewModel, UnityAction`1, UnityAction)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signCheckinItemViewHolder : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private ActivityCommonCheckinV2Item _normalItemPrefab; // 0x20
	private Act29signSpecialCheckinItem _specialItemPrefab; // 0x28
	private ActivityCommonCheckinV2Item m_normalItem; // 0x30
	private Act29signSpecialCheckinItem m_specialItem; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x32601a0 VA: 0x75958781a0
	public Void Render(Act29signSpecialCheckinItemViewModel data, UnityAction`1 onNormalItemClicked, UnityAction onSpecialItemClicked) { }
	// RVA: 0x32609d8 VA: 0x75958789d8
	public Void .ctor() { }
}
```