# CrossAppShareRemakeDynAssetContent

**Namespace:** `Torappu.UI.CrossAppShare`


## Fields

- `ILoadAsset m_iLoadAsset`


## Methods

- `Void ApplyDynAsset(CrossAppShareDynAssetBaseModel, ILoadAsset)`

- `Void _ApplyAvatar(CrossAppShareAvatarModel)`

- `Void _ApplyFriendMedal(CrossAppShareMedalModel)`

- `Void _ApplyIllust(CrossAppShareIllustModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrossAppShare
public class CrossAppShareRemakeDynAssetContent : MonoBehaviour, IHotfixable
{
	private ILoadAsset m_iLoadAsset; // 0x18
	private static DelegateBridge __Hotfix0_ApplyDynAsset; // 0x0
	private static DelegateBridge __Hotfix0__ApplyAvatar; // 0x8
	private static DelegateBridge __Hotfix0__ApplyFriendMedal; // 0x10
	private static DelegateBridge __Hotfix0__ApplyIllust; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2bc176c VA: 0x75951d976c
	public Void ApplyDynAsset(CrossAppShareDynAssetBaseModel dynAssetModel, ILoadAsset iLoadAsset) { }
	// RVA: 0x2bc192c VA: 0x75951d992c
	private Void _ApplyAvatar(CrossAppShareAvatarModel avatarModel) { }
	// RVA: 0x2bc1a84 VA: 0x75951d9a84
	private Void _ApplyFriendMedal(CrossAppShareMedalModel medalModel) { }
	// RVA: 0x2bc1cdc VA: 0x75951d9cdc
	private Void _ApplyIllust(CrossAppShareIllustModel illustModel) { }
	// RVA: 0x2bc1ea8 VA: 0x75951d9ea8
	public Void .ctor() { }
}
```