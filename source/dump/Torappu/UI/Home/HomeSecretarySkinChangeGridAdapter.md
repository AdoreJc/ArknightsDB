# HomeSecretarySkinChangeGridAdapter

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _prefab`

- `String m_previewSkinId`


## Methods

- `Void SetArguments(HashSet`1, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinChangeGridAdapter : LoopScrollAdapter`2
{
	private GameObject _prefab; // 0x58
	private HashSet`1 m_selectedSkinIds; // 0x60
	private String m_previewSkinId; // 0x68
	private static DelegateBridge __Hotfix0_SetArguments; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x283ea08 VA: 0x7594e56a08
	public Void SetArguments(HashSet`1 selectedIds, String previewId) { }
	// RVA: 0x283eaa4 VA: 0x7594e56aa4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, HomeSecretarySkinItemModel data) { }
	// RVA: 0x283ed9c VA: 0x7594e56d9c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x283ee5c VA: 0x7594e56e5c
	public Void .ctor() { }
}
```