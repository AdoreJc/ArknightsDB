# ActMultiV3PhotoAvatarListAdapter

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _avatarObjPrefab`

- `Int32 m_cachedSelectedIdx`


## Properties

- `Int32 selectedIdx`


## Methods

- `Void set_selectedIdx(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoAvatarListAdapter : LoopScrollAdapter`2
{
	private GameObject _avatarObjPrefab; // 0x58
	private Int32 m_cachedSelectedIdx; // 0x60
	private static DelegateBridge __Hotfix0_set_selectedIdx; // 0x0
	private static DelegateBridge __Hotfix0_CreateView; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Int32 selectedIdx { set; }

	// RVA: 0x311be04 VA: 0x7595733e04
	public Void set_selectedIdx(Int32 value) { }
	// RVA: 0x311be80 VA: 0x7595733e80
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x311bf40 VA: 0x7595733f40
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, ActMultiV3PhotoDetailViewModel data) { }
	// RVA: 0x311c0a8 VA: 0x75957340a8
	public Void .ctor() { }
}
```