# HomeSecretaryChangeGridAdapter

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _charCardViewPrefab`

- `Int32 m_previewingInstId`


## Methods

- `Void SetArguments(HashSet`1, HashSet`1, Dictionary`2, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretaryChangeGridAdapter : HomeSecretaryCardScrollAdapter`1
{
	private const Int32 DEFAULT_SKIN_NUM; // 0x0
	private GameObject _charCardViewPrefab; // 0x60
	private HashSet`1 m_selectedChrInstIds; // 0x68
	private HashSet`1 m_starMarkSelectedInstIds; // 0x70
	private Dictionary`2 m_inPresetSkinDict; // 0x78
	private Int32 m_previewingInstId; // 0x80
	private static DelegateBridge __Hotfix0_SetArguments; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x283d1bc VA: 0x7594e551bc
	public Void SetArguments(HashSet`1 selectedInstIds, HashSet`1 starMarkSelectedInstIds, Dictionary`2 inPresetSkinDict, Int32 previewInstId) { }
	// RVA: 0x283d28c VA: 0x7594e5528c
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, HomeSecretaryCardViewModel data) { }
	// RVA: 0x283d510 VA: 0x7594e55510
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x283d5d0 VA: 0x7594e555d0
	public Void .ctor() { }
}
```