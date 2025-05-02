# HandBookInfoStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookInfoViewModel viewModel`

- `HandBookCardViewModel selectedCard`

- `CharacterIllustViewProperty illustProperty`

- `TrackPointViewProperty avgTrackPointProperty`

- `TrackPointViewProperty stageTrackPointProperty`

- `String drawName`

- `Boolean haveDesigner`

- `String designerName`

- `String infoName`

- `Boolean hasMultiVoiceLang`

- `Boolean hasNoResForVoiceLang`

- `HandBookVoiceLangViewProperty voiceLangViewProperty`

- `TrackPointViewProperty newVoiceTrackPointProperty`

- `HandBookDesignerViewProperty designerViewProperty`


## Methods

- `Void LoadData(String, Boolean)`

- `Void LoadData(CharViewModel)`

- `Void _LoadCVInfo(HandBookCardViewModel)`

- `Void LoadData(HandBookCardViewModel)`

- `Boolean TryFindAvgData(String, out, out)`

- `Void RefreshVoiceLangInfo()`

- `HandBookStoryViewModel <LoadData>b__19_0(HandBookStoryViewData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public HandBookInfoViewModel viewModel; // 0x18
	public HandBookCardViewModel selectedCard; // 0x20
	public CharacterIllustViewProperty illustProperty; // 0x28
	public TrackPointViewProperty avgTrackPointProperty; // 0x30
	public TrackPointViewProperty stageTrackPointProperty; // 0x38
	public String drawName; // 0x40
	public Boolean haveDesigner; // 0x48
	public String designerName; // 0x50
	public String infoName; // 0x58
	public Boolean hasMultiVoiceLang; // 0x60
	public Boolean hasNoResForVoiceLang; // 0x61
	public HandBookVoiceLangViewProperty voiceLangViewProperty; // 0x68
	public TrackPointViewProperty newVoiceTrackPointProperty; // 0x70
	public HandBookDesignerViewProperty designerViewProperty; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix1_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__LoadCVInfo; // 0x10
	private static DelegateBridge __Hotfix2_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_TryFindAvgData; // 0x20
	private static DelegateBridge __Hotfix0_RefreshVoiceLangInfo; // 0x28
	private static DelegateBridge __Hotfix0__LoadNPCCharTextInfo; // 0x30
	private static DelegateBridge __Hotfix0__LoadCommonCharTextInfo; // 0x38
	private static DelegateBridge __Hotfix0__LoadCharTextInfo; // 0x40
	private static DelegateBridge __Hotfix0__TryToLoadVoiceLangInfoFromCard; // 0x48
	private static DelegateBridge __Hotfix0__TryToLoadVoiceLangInfo; // 0x50
	private static DelegateBridge __Hotfix0_CheckAllCardShow; // 0x58
	private static DelegateBridge __Hotfix0_CheckCardShow; // 0x60
	private static DelegateBridge __Hotfix0_CheckCardUnlock; // 0x68
	private static DelegateBridge __Hotfix0_CheckCardisLocked; // 0x70
	private static DelegateBridge __Hotfix0_CheckExist; // 0x78
	private static DelegateBridge __Hotfix1_CheckExist; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x2ebabe8 VA: 0x75954d2be8
	public Void LoadData(String charIdImport, Boolean isNPC) { }
	// RVA: 0x2ebbb94 VA: 0x75954d3b94
	public Void LoadData(CharViewModel charDetailModel) { }
	// RVA: 0x2ebbdc4 VA: 0x75954d3dc4
	private Void _LoadCVInfo(HandBookCardViewModel selectedCardData) { }
	// RVA: 0x2ebaf88 VA: 0x75954d2f88
	public Void LoadData(HandBookCardViewModel selectedCardData) { }
	// RVA: 0x2ebcc8c VA: 0x75954d4c8c
	public Boolean TryFindAvgData(String storyId, out HandbookAvgGroupData groupData, out HandbookAvgData avgData) { }
	// RVA: 0x2ebcf40 VA: 0x75954d4f40
	public Void RefreshVoiceLangInfo() { }
	// RVA: 0x2ebd040 VA: 0x75954d5040
	private List`1 _LoadNPCCharTextInfo(HandBookCardViewModel cardData) { }
	// RVA: 0x2ebd4b4 VA: 0x75954d54b4
	private List`1 _LoadCommonCharTextInfo(HandBookCardViewModel cardData) { }
	// RVA: 0x2ebc400 VA: 0x75954d4400
	private List`1 _LoadCharTextInfo(HandBookCardViewModel cardData) { }
	// RVA: 0x2ebbf6c VA: 0x75954d3f6c
	private static Boolean _TryToLoadVoiceLangInfoFromCard(HandBookCardViewModel cardData, out VoiceLangInfoStruct voiceLangInfo) { }
	// RVA: 0x2ebd9ec VA: 0x75954d59ec
	private static Boolean _TryToLoadVoiceLangInfo(String skinId, VoiceLangType voiceLangType, ref VoiceLangInfoStruct voiceLangInfo) { }
	// RVA: 0x2ebe174 VA: 0x75954d6174
	public static Boolean CheckAllCardShow(HandBookCardViewModel cardData, HandBookStoryViewData dataInfo, out List`1 result) { }
	// RVA: 0x2ebe378 VA: 0x75954d6378
	public static Boolean CheckCardShow(HandBookCardViewModel cardData, StoryText storyText) { }
	// RVA: 0x2ebe404 VA: 0x75954d6404
	public static Boolean CheckCardUnlock(HandBookCardViewModel cardData, StoryText storyText) { }
	// RVA: 0x2ebe4b4 VA: 0x75954d64b4
	public static Boolean CheckCardisLocked(HandBookCardViewModel cardData, StoryText storyText) { }
	// RVA: 0x2eba5c8 VA: 0x75954d25c8
	public static Boolean CheckExist(HandBookCardViewModel cardData, DataUnlockType type, String param) { }
	// RVA: 0x2ebcb7c VA: 0x75954d4b7c
	public static Boolean CheckExist(HandBookCardViewModel cardData, HandBookStoryViewModel viewModel) { }
	// RVA: 0x2ebe564 VA: 0x75954d6564
	public Void .ctor() { }
	// RVA: 0x2ebe7c0 VA: 0x75954d67c0
	private HandBookStoryViewModel <LoadData>b__19_0(HandBookStoryViewData src) { }
}
```