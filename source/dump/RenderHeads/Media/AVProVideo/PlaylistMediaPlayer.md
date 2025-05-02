# PlaylistMediaPlayer

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _playerA`

- `MediaPlayer _playerB`

- `Boolean _playlistAutoProgress`

- `Boolean _autoCloseVideo`

- `PlaylistLoopMode _playlistLoopMode`

- `MediaPlaylist _playlist`

- `Boolean _pausePreviousOnTransition`

- `Transition _nextTransition`

- `Single _transitionDuration`

- `Easing _transitionEasing`

- `Int32 _playlistIndex`

- `MediaPlayer _nextPlayer`

- `Shader _shader`

- `Material _material`

- `Transition _currentTransition`

- `String _currentTransitionName`

- `Single _currentTransitionDuration`

- `Preset _currentTransitionEasing`

- `Single _textureTimer`

- `Single _transitionTimer`

- `RenderTexture _rt`

- `MediaItem _currentItem`

- `MediaItem _nextItem`


## Properties

- `MediaPlayer CurrentPlayer`

- `MediaPlayer NextPlayer`

- `MediaPlaylist Playlist`

- `Int32 PlaylistIndex`

- `MediaItem PlaylistItem`

- `PlaylistLoopMode LoopMode`

- `Boolean AutoProgress`


## Methods

- `MediaPlayer get_CurrentPlayer()`

- `MediaPlayer get_NextPlayer()`

- `MediaPlaylist get_Playlist()`

- `Int32 get_PlaylistIndex()`

- `MediaItem get_PlaylistItem()`

- `PlaylistLoopMode get_LoopMode()`

- `Void set_LoopMode(PlaylistLoopMode)`

- `Boolean get_AutoProgress()`

- `Void set_AutoProgress(Boolean)`

- `Void SwapPlayers()`

- `Texture GetCurrentTexture()`

- `Texture GetNextTexture()`

- `Void Awake()`

- `Void Start()`

- `Void OnVideoEvent(MediaPlayer, EventType, ErrorCode)`

- `Boolean PrevItem()`

- `Boolean NextItem()`

- `Boolean CanJumpToItem(Int32)`

- `Boolean JumpToItem(Int32)`

- `Void OpenVideoFile(MediaItem)`

- `Boolean IsTransitioning()`

- `Void SetTransition(Transition, Single, Preset)`

- `Texture GetTexture(Int32)`

- `Int32 GetTextureCount()`

- `Int32 GetTextureFrameCount()`

- `Boolean SupportsTextureFrameCount()`

- `Int64 GetTextureTimeStamp()`

- `Boolean RequiresVerticalFlip()`

- `Matrix4x4 GetYpCbCrTransform()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class PlaylistMediaPlayer : MediaPlayer, IMediaProducer
{
	private MediaPlayer _playerA; // 0x180
	private MediaPlayer _playerB; // 0x188
	private Boolean _playlistAutoProgress; // 0x190
	private Boolean _autoCloseVideo; // 0x191
	private PlaylistLoopMode _playlistLoopMode; // 0x194
	private MediaPlaylist _playlist; // 0x198
	private Boolean _pausePreviousOnTransition; // 0x1a0
	private Transition _nextTransition; // 0x1a4
	private Single _transitionDuration; // 0x1a8
	private Easing _transitionEasing; // 0x1b0
	private static Int32 _propFromTex; // 0x0
	private static Int32 _propT; // 0x4
	private Int32 _playlistIndex; // 0x1b8
	private MediaPlayer _nextPlayer; // 0x1c0
	private Shader _shader; // 0x1c8
	private Material _material; // 0x1d0
	private Transition _currentTransition; // 0x1d8
	private String _currentTransitionName; // 0x1e0
	private Single _currentTransitionDuration; // 0x1e8
	private Preset _currentTransitionEasing; // 0x1ec
	private Single _textureTimer; // 0x1f0
	private Single _transitionTimer; // 0x1f4
	private Func`2 _easeFunc; // 0x1f8
	private RenderTexture _rt; // 0x200
	private MediaItem _currentItem; // 0x208
	private MediaItem _nextItem; // 0x210

	public MediaPlayer CurrentPlayer { get; }
	public MediaPlayer NextPlayer { get; }
	public MediaPlaylist Playlist { get; }
	public Int32 PlaylistIndex { get; }
	public MediaItem PlaylistItem { get; }
	public PlaylistLoopMode LoopMode { get; set; }
	public Boolean AutoProgress { get; set; }
	public override IMediaInfo Info { get; }
	public override IMediaControl Control { get; }
	public override IMediaProducer TextureProducer { get; }

	// RVA: 0x66864d8 VA: 0x7598c9e4d8
	public MediaPlayer get_CurrentPlayer() { }
	// RVA: 0x6686554 VA: 0x7598c9e554
	public MediaPlayer get_NextPlayer() { }
	// RVA: 0x668655c VA: 0x7598c9e55c
	public MediaPlaylist get_Playlist() { }
	// RVA: 0x6686564 VA: 0x7598c9e564
	public Int32 get_PlaylistIndex() { }
	// RVA: 0x668656c VA: 0x7598c9e56c
	public MediaItem get_PlaylistItem() { }
	// RVA: 0x66865ec VA: 0x7598c9e5ec
	public PlaylistLoopMode get_LoopMode() { }
	// RVA: 0x66865f4 VA: 0x7598c9e5f4
	public Void set_LoopMode(PlaylistLoopMode value) { }
	// RVA: 0x66865fc VA: 0x7598c9e5fc
	public Boolean get_AutoProgress() { }
	// RVA: 0x6686604 VA: 0x7598c9e604
	public Void set_AutoProgress(Boolean value) { }
	// RVA: 0x6686610 VA: 0x7598c9e610
	public override IMediaInfo get_Info() { }
	// RVA: 0x66866ac VA: 0x7598c9e6ac
	public override IMediaControl get_Control() { }
	// RVA: 0x6686748 VA: 0x7598c9e748
	public override IMediaProducer get_TextureProducer() { }
	// RVA: 0x6686884 VA: 0x7598c9e884
	private Void SwapPlayers() { }
	// RVA: 0x6686bec VA: 0x7598c9ebec
	private Texture GetCurrentTexture() { }
	// RVA: 0x6686d20 VA: 0x7598c9ed20
	private Texture GetNextTexture() { }
	// RVA: 0x6687204 VA: 0x7598c9f204
	private Void Awake() { }
	// RVA: 0x6687350 VA: 0x7598c9f350
	protected override Void OnDestroy() { }
	// RVA: 0x6687438 VA: 0x7598c9f438
	private Void Start() { }
	// RVA: 0x668768c VA: 0x7598c9f68c
	public Void OnVideoEvent(MediaPlayer mp, EventType et, ErrorCode errorCode) { }
	// RVA: 0x66878a8 VA: 0x7598c9f8a8
	public Boolean PrevItem() { }
	// RVA: 0x6687828 VA: 0x7598c9f828
	public Boolean NextItem() { }
	// RVA: 0x66878b4 VA: 0x7598c9f8b4
	public Boolean CanJumpToItem(Int32 index) { }
	// RVA: 0x66875a4 VA: 0x7598c9f5a4
	public Boolean JumpToItem(Int32 index) { }
	// RVA: 0x6687938 VA: 0x7598c9f938
	public Void OpenVideoFile(MediaItem mediaItem) { }
	// RVA: 0x66867f8 VA: 0x7598c9e7f8
	private Boolean IsTransitioning() { }
	// RVA: 0x6687ad4 VA: 0x7598c9fad4
	private Void SetTransition(Transition transition, Single duration, Preset easing) { }
	// RVA: 0x6687cf0 VA: 0x7598c9fcf0
	protected override Void Update() { }
	// RVA: 0x66881e0 VA: 0x7598ca01e0
	public Texture GetTexture(Int32 index) { }
	// RVA: 0x66881e8 VA: 0x7598ca01e8
	public Int32 GetTextureCount() { }
	// RVA: 0x66882a0 VA: 0x7598ca02a0
	public Int32 GetTextureFrameCount() { }
	// RVA: 0x668835c VA: 0x7598ca035c
	public Boolean SupportsTextureFrameCount() { }
	// RVA: 0x6688418 VA: 0x7598ca0418
	public Int64 GetTextureTimeStamp() { }
	// RVA: 0x66884d4 VA: 0x7598ca04d4
	public Boolean RequiresVerticalFlip() { }
	// RVA: 0x6688590 VA: 0x7598ca0590
	public Matrix4x4 GetYpCbCrTransform() { }
	// RVA: 0x6687b90 VA: 0x7598c9fb90
	private static String GetTransitionName(Transition transition) { }
	// RVA: 0x6688670 VA: 0x7598ca0670
	public Void .ctor() { }
}
```