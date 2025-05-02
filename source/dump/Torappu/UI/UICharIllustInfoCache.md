# UICharIllustInfoCache

**Namespace:** `Torappu.UI`


## Fields

- `String m_presetInstId`

- `Int32 m_displaySkinIndex`


## Methods

- `UIIllustLayoutInfo GetUserIllustInfo(String, DisplayType)`

- `Void SaveUserIllustInfo(String, DisplayType, UIIllustLayoutInfo)`

- `Void RecordDefault(String, UICharacterIllust)`

- `UIIllustLayoutInfo GetDefault(String)`

- `Void TryUpdateCharRotationForLogin()`

- `Void GenerateSkinListWithSpecifiedSkinNotFirst(String, String)`

- `Void GenerateSkinListWithSpecifiedSkinFirst(String, String)`

- `Void SetDisplaySkin(String, String)`

- `String GetCurrentDisplaySkinId(String)`

- `UIIllustLayoutInfo _GetUserIllustForHome(String)`

- `Void _SaveUserIllustForHome(String, UIIllustLayoutInfo)`

- `Boolean _UpdateCondCheck()`

- `Void _LoadCharRotationInfoIfNot()`

- `Void _SaveUserCharRotationSkinList(String, List`1, Int32)`

- `Boolean _CheckIfCacheMatchWithPlayerData(String)`

- `Void _GenerateSkinList(String, String, CharRotationGenerateHandler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharIllustInfoCache : IHotfixable
{
	private const Int32 HOME_ILLUST_VER; // 0x0
	private Dictionary`2 m_homeIllusts; // 0x10
	private Dictionary`2 m_defaultIllusts; // 0x18
	private String m_presetInstId; // 0x20
	private Int32 m_displaySkinIndex; // 0x28
	private List`1 m_rotateSkinList; // 0x30
	private static DelegateBridge __Hotfix0_GetUserIllustInfo; // 0x0
	private static DelegateBridge __Hotfix0_SaveUserIllustInfo; // 0x8
	private static DelegateBridge __Hotfix0_RecordDefault; // 0x10
	private static DelegateBridge __Hotfix0_GetDefault; // 0x18
	private static DelegateBridge __Hotfix0_TryUpdateCharRotationForLogin; // 0x20
	private static DelegateBridge __Hotfix0_GenerateSkinListWithSpecifiedSkinNotFirst; // 0x28
	private static DelegateBridge __Hotfix0_GenerateSkinListWithSpecifiedSkinFirst; // 0x30
	private static DelegateBridge __Hotfix0_SetDisplaySkin; // 0x38
	private static DelegateBridge __Hotfix0_GetCurrentDisplaySkinId; // 0x40
	private static DelegateBridge __Hotfix0__GetUserIllustForHome; // 0x48
	private static DelegateBridge __Hotfix0__InitIllusts; // 0x50
	private static DelegateBridge __Hotfix0__SaveUserIllustForHome; // 0x58
	private static DelegateBridge __Hotfix0__UpdateCondCheck; // 0x60
	private static DelegateBridge __Hotfix0__LoadCharRotationInfoIfNot; // 0x68
	private static DelegateBridge __Hotfix0__SaveUserCharRotationSkinList; // 0x70
	private static DelegateBridge __Hotfix0__CheckIfCacheMatchWithPlayerData; // 0x78
	private static DelegateBridge __Hotfix0__GetSkinListFromPlayerPreset; // 0x80
	private static DelegateBridge __Hotfix0__ShuffleAndSetSpecifiedSkinFirst; // 0x88
	private static DelegateBridge __Hotfix0__ShuffleAndSetSpecifiedSkinNotFirst; // 0x90
	private static DelegateBridge __Hotfix0__GenerateSkinList; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x211c748 VA: 0x7594734748
	public UIIllustLayoutInfo GetUserIllustInfo(String illustId, DisplayType type) { }
	// RVA: 0x211c924 VA: 0x7594734924
	public Void SaveUserIllustInfo(String illustId, DisplayType type, UIIllustLayoutInfo info) { }
	// RVA: 0x2119b24 VA: 0x7594731b24
	public Void RecordDefault(String illustId, UICharacterIllust illust) { }
	// RVA: 0x211cb2c VA: 0x7594734b2c
	public UIIllustLayoutInfo GetDefault(String illustId) { }
	// RVA: 0x211cc18 VA: 0x7594734c18
	public Void TryUpdateCharRotationForLogin() { }
	// RVA: 0x211d180 VA: 0x7594735180
	public Void GenerateSkinListWithSpecifiedSkinNotFirst(String instId, String skinId) { }
	// RVA: 0x211d804 VA: 0x7594735804
	public Void GenerateSkinListWithSpecifiedSkinFirst(String instId, String skinId) { }
	// RVA: 0x211d8e4 VA: 0x75947358e4
	public Void SetDisplaySkin(String instId, String skinId) { }
	// RVA: 0x211d3c0 VA: 0x75947353c0
	public String GetCurrentDisplaySkinId(String instId) { }
	// RVA: 0x211c814 VA: 0x7594734814
	private UIIllustLayoutInfo _GetUserIllustForHome(String illustId) { }
	// RVA: 0x211da64 VA: 0x7594735a64
	private static Void _InitIllusts(String key, out Dictionary`2 illusts) { }
	// RVA: 0x211c9f8 VA: 0x75947349f8
	private Void _SaveUserIllustForHome(String illustId, UIIllustLayoutInfo info) { }
	// RVA: 0x211d260 VA: 0x7594735260
	private Boolean _UpdateCondCheck() { }
	// RVA: 0x211cdb0 VA: 0x7594734db0
	private Void _LoadCharRotationInfoIfNot() { }
	// RVA: 0x211d4ac VA: 0x75947354ac
	private Void _SaveUserCharRotationSkinList(String instId, List`1 skinList, Int32 displayIndex) { }
	// RVA: 0x211cf08 VA: 0x7594734f08
	private Boolean _CheckIfCacheMatchWithPlayerData(String instId) { }
	// RVA: 0x211db70 VA: 0x7594735b70
	private static List`1 _GetSkinListFromPlayerPreset(String instId) { }
	// RVA: 0x211de54 VA: 0x7594735e54
	private static Void _ShuffleAndSetSpecifiedSkinFirst(List`1 list, String skinId) { }
	// RVA: 0x211dfe4 VA: 0x7594735fe4
	private static Void _ShuffleAndSetSpecifiedSkinNotFirst(List`1 list, String skinId) { }
	// RVA: 0x211d720 VA: 0x7594735720
	private Void _GenerateSkinList(String instId, String specifiedSkinId, CharRotationGenerateHandler handler) { }
	// RVA: 0x211e190 VA: 0x7594736190
	public Void .ctor() { }
}
```