# UIChatBoxView

**Namespace:** `Torappu.UI.ChatBox`


## Fields

- `ScrollRect _chatScroll`

- `UIRecycleLayoutGroup _chatLayout`

- `Graphic _scrollRaycaster`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `PlayHandler m_activePlayer`


## Methods

- `Void _InitIfNot()`

- `PlayHandler PlayChat(PlayOptions)`

- `Void AppendPlayRecords(IEnumerable`1)`

- `Void DisplayChat(DisplayOptions)`

- `Void ClearChat()`

- `Void RequestScrollRaycast(ScrollRaycastRequestKey)`

- `Void ReleaseScrollRaycast(ScrollRaycastRequestKey)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChatBox
public class UIChatBoxView : MonoBehaviour, IHotfixable
{
	private ScrollRect _chatScroll; // 0x18
	private UIRecycleLayoutGroup _chatLayout; // 0x20
	private Graphic _scrollRaycaster; // 0x28
	private Boolean m_isInited; // 0x30
	private Adapter m_adapter; // 0x38
	private List`1 m_chatItems; // 0x40
	private PlayHandler m_activePlayer; // 0x48
	private ListSet`1 m_requests; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_PlayChat; // 0x8
	private static DelegateBridge __Hotfix0_AppendPlayRecords; // 0x10
	private static DelegateBridge __Hotfix0_DisplayChat; // 0x18
	private static DelegateBridge __Hotfix0_ClearChat; // 0x20
	private static DelegateBridge __Hotfix0_RequestScrollRaycast; // 0x28
	private static DelegateBridge __Hotfix0_ReleaseScrollRaycast; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2c41974 VA: 0x7595259974
	private Void _InitIfNot() { }
	// RVA: 0x2c41b24 VA: 0x7595259b24
	public PlayHandler PlayChat(PlayOptions playOptions) { }
	// RVA: 0x2c41f3c VA: 0x7595259f3c
	public Void AppendPlayRecords(IEnumerable`1 records) { }
	// RVA: 0x2c420d8 VA: 0x759525a0d8
	public Void DisplayChat(DisplayOptions options) { }
	// RVA: 0x2c42304 VA: 0x759525a304
	public Void ClearChat() { }
	// RVA: 0x2c423e8 VA: 0x759525a3e8
	public Void RequestScrollRaycast(ScrollRaycastRequestKey key) { }
	// RVA: 0x2c41c40 VA: 0x7595259c40
	public Void ReleaseScrollRaycast(ScrollRaycastRequestKey key) { }
	// RVA: 0x2c4250c VA: 0x759525a50c
	private Void Update() { }
	// RVA: 0x2c42714 VA: 0x759525a714
	public Void .ctor() { }
}
```