# ActMultiV3EmoticonController

**Namespace:** `Torappu.Activity.ActMultiV3`


## Methods

- `GOPositionHolder GetPanelPos(LeftChatPosType)`

- `GOPositionHolder GetReceiveEmojiPosData(LeftChatPosType, PlayerIndex)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EmoticonController : EmoticonPagerPanelBaseController
{
	private List`1 _panelPosTypeDataList; // 0x68
	private List`1 _receiveEmojiPosDataList; // 0x70
	private static DelegateBridge __Hotfix0__OnSendEmoji; // 0x0
	private static DelegateBridge __Hotfix0_GetPanelPos; // 0x8
	private static DelegateBridge __Hotfix0_GetReceiveEmojiPosData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30e67f4 VA: 0x75956fe7f4
	protected override Void _OnSendEmoji(String themeId, String emojiItem) { }
	// RVA: 0x30e6958 VA: 0x75956fe958
	public GOPositionHolder GetPanelPos(LeftChatPosType leftChatPosType) { }
	// RVA: 0x30e6ab0 VA: 0x75956feab0
	public GOPositionHolder GetReceiveEmojiPosData(LeftChatPosType leftChatPosType, PlayerIndex pos) { }
	// RVA: 0x30e6bf8 VA: 0x75956febf8
	public Void .ctor() { }
}
```