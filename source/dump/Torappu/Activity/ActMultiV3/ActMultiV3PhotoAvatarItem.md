# ActMultiV3PhotoAvatarItem

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Transform _avatarContainer`

- `GameObject _comittedPart`

- `GameObject _selectedPart`

- `RectTransform _newTrackContainer`

- `GameObject _newTrackObject`

- `GameObject _selectHotspotGo`

- `UIColorGraphic _selectTargetGraphic`

- `Boolean m_inited`

- `Int32 m_cachedPhotoIdx`

- `UIStateFinder m_stateFinder`

- `GameObject m_newTrackObject`

- `PlayerAvatarView m_avatarView`


## Methods

- `Void Render(ActMultiV3PhotoDetailViewModel, Int32, Int32)`

- `Void OnSelectPhoto()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoAvatarItem : MonoBehaviour, IHotfixable
{
	private Transform _avatarContainer; // 0x18
	private GameObject _comittedPart; // 0x20
	private GameObject _selectedPart; // 0x28
	private RectTransform _newTrackContainer; // 0x30
	private GameObject _newTrackObject; // 0x38
	private GameObject _selectHotspotGo; // 0x40
	private UIColorGraphic _selectTargetGraphic; // 0x48
	private Boolean m_inited; // 0x50
	private Int32 m_cachedPhotoIdx; // 0x54
	private UIStateFinder m_stateFinder; // 0x58
	private GameObject m_newTrackObject; // 0x68
	private PlayerAvatarView m_avatarView; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectPhoto; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x311b9b4 VA: 0x75957339b4
	public Void Render(ActMultiV3PhotoDetailViewModel model, Int32 idx, Int32 selectedIdx) { }
	// RVA: 0x311bc9c VA: 0x7595733c9c
	public Void OnSelectPhoto() { }
	// RVA: 0x311bae0 VA: 0x7595733ae0
	private Void _InitIfNot() { }
	// RVA: 0x311bd8c VA: 0x7595733d8c
	public Void .ctor() { }
}
```