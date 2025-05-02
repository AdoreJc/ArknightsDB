# FriendNameCardMedalView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendNameCardMedalItem _itemView`

- `NameCardSelectViewModel viewModel`

- `UINameCardEvent onClickEvent`

- `UIPageListener m_pageListener`


## Properties

- `UIPageListener pageListener`


## Methods

- `UIPageListener get_pageListener()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendNameCardMedalView : RecycleLoopScrollAdapter
{
	private FriendNameCardMedalItem _itemView; // 0x58
	public NameCardSelectViewModel viewModel; // 0x60
	public UINameCardEvent onClickEvent; // 0x68
	private UIPageListener m_pageListener; // 0x70
	private static DelegateBridge __Hotfix0_get_pageListener; // 0x0
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected UIPageListener pageListener { get; }
	public override Int32 totalCount { get; }

	// RVA: 0x28dc750 VA: 0x7594ef4750
	protected UIPageListener get_pageListener() { }
	// RVA: 0x28dc818 VA: 0x7594ef4818
	public override Int32 get_totalCount() { }
	// RVA: 0x28dc8ac VA: 0x7594ef48ac
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x28dcb88 VA: 0x7594ef4b88
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x28dcc98 VA: 0x7594ef4c98
	public Void .ctor() { }
}
```