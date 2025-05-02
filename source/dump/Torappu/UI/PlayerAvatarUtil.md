# PlayerAvatarUtil

**Namespace:** `Torappu.UI`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PlayerAvatarUtil : IHotfixable
{
	private static DelegateBridge __Hotfix0_IsAssistantType; // 0x0
	private static DelegateBridge __Hotfix0_GetAvatarIcon; // 0x8
	private static DelegateBridge __Hotfix1_GetAvatarIcon; // 0x10
	private static DelegateBridge __Hotfix2_GetAvatarIcon; // 0x18
	private static DelegateBridge __Hotfix0_GetAvatarIconByAvatarData; // 0x20
	private static DelegateBridge __Hotfix1_GetAvatarIconByAvatarData; // 0x28
	private static DelegateBridge __Hotfix0_GetAssistantName; // 0x30
	private static DelegateBridge __Hotfix0_GetAvatarViewPrefab; // 0x38
	private static DelegateBridge __Hotfix0__GetAvatarIconFromAssistant; // 0x40
	private static DelegateBridge __Hotfix0__GetDefaultAvatar; // 0x48
	private static DelegateBridge __Hotfix0__GetAvatarIconFromHub; // 0x50
	private static DelegateBridge __Hotfix1__GetAvatarIconFromHub; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x22765e0 VA: 0x759488e5e0
	public static Boolean IsAssistantType(PlayerAvatarType avatarType) { }
	// RVA: 0x227664c VA: 0x759488e64c
	public static Sprite GetAvatarIcon(AvatarInfo avatarInfo, String pageName) { }
	// RVA: 0x22768f8 VA: 0x759488e8f8
	public static Sprite GetAvatarIcon(String avatarId, PlayerAvatarType avatarType, ILoadAsset loader) { }
	// RVA: 0x2276aec VA: 0x759488eaec
	public static Sprite GetAvatarIcon(AvatarInfo avatarInfo, ILoadAsset loader) { }
	// RVA: 0x2276b88 VA: 0x759488eb88
	public static Sprite GetAvatarIconByAvatarData(String avatarId, PlayerAvatarGroupType groupType, String pageName) { }
	// RVA: 0x2276c70 VA: 0x759488ec70
	public static Sprite GetAvatarIconByAvatarData(String avatarId, PlayerAvatarGroupType groupType, ILoadAsset loader) { }
	// RVA: 0x2276d64 VA: 0x759488ed64
	public static String GetAssistantName() { }
	// RVA: 0x2276e6c VA: 0x759488ee6c
	public static PlayerAvatarView GetAvatarViewPrefab() { }
	// RVA: 0x22767fc VA: 0x759488e7fc
	private static Sprite _GetAvatarIconFromAssistant(String skinId) { }
	// RVA: 0x22769c8 VA: 0x759488e9c8
	private static Sprite _GetDefaultAvatar(ILoadAsset loader) { }
	// RVA: 0x2276744 VA: 0x759488e744
	private static Sprite _GetAvatarIconFromHub(String avatarId, String pageName) { }
	// RVA: 0x2276a60 VA: 0x759488ea60
	private static Sprite _GetAvatarIconFromHub(String avatarId, ILoadAsset loader) { }
	// RVA: 0x2276f14 VA: 0x759488ef14
	public Void .ctor() { }
}
```