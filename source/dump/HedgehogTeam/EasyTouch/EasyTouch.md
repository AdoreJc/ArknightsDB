# EasyTouch

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `Gesture _currentGesture`

- `Boolean enable`

- `Boolean enableRemote`

- `GesturePriority gesturePriority`

- `Single StationaryTolerance`

- `Single longTapTime`

- `Single swipeTolerance`

- `Single minPinchLength`

- `Single minTwistAngle`

- `DoubleTapDetection doubleTapDetection`

- `Single doubleTapTime`

- `Boolean alwaysSendSwipe`

- `Boolean enable2FingersGesture`

- `Boolean enableTwist`

- `Boolean enablePinch`

- `Boolean enable2FingersSwipe`

- `TwoFingerPickMethod twoFingerPickMethod`

- `Boolean autoSelect`

- `LayerMask pickableLayers3D`

- `Boolean enable2D`

- `LayerMask pickableLayers2D`

- `Boolean autoUpdatePickedObject`

- `Boolean allowUIDetection`

- `Boolean enableUIMode`

- `Boolean autoUpdatePickedUI`

- `Boolean enabledNGuiMode`

- `LayerMask nGUILayers`

- `Boolean enableSimulation`

- `KeyCode twistKey`

- `KeyCode swipeKey`

- `Boolean showGuiInspector`

- `Boolean showSelectInspector`

- `Boolean showGestureInspector`

- `Boolean showTwoFingerInspector`

- `Boolean showSecondFingerInspector`

- `EasyTouchInput input`

- `Texture secondFingerTexture`

- `TwoFingerGesture twoFinger`

- `Int32 oldTouchCount`

- `PickedObject pickedObject`

- `PointerEventData uiPointerEventData`

- `EventSystem uiEventSystem`


## Methods

- `Void OnEnable()`

- `Void Awake()`

- `Void Start()`

- `Void Init()`

- `Void OnDrawGizmos()`

- `Void Update()`

- `Void LateUpdate()`

- `Void UpdateTouches(Boolean, Int32)`

- `Void ResetTouches()`

- `Void OneFinger(Int32)`

- `IEnumerator SingleOrDouble(Int32)`

- `Void CreateGesture(Int32, EvtType, Finger, SwipeDirection, Single, Vector2)`

- `Void TwoFinger()`

- `Void DetectPinch(Single)`

- `Void DetecTwist(Vector2, Vector2, Single)`

- `Void CreateStateEnd2Fingers(GestureType, Vector2, Vector2, Vector2, Single, Boolean, Single, Single, Single)`

- `IEnumerator SingleOrDouble2Fingers()`

- `Void CreateGesture2Finger(EvtType, Vector2, Vector2, Vector2, Single, SwipeDirection, Single, Vector2, Single, Single, Single)`

- `Int32 GetTwoFinger(Int32)`

- `Boolean GetTwoFingerPickedObject()`

- `Boolean GetTwoFingerPickedUIElement()`

- `Void RaiseEvent(EvtType, Gesture)`

- `Boolean GetPickedGameObject(Finger, Boolean)`

- `Boolean GetGameObjectAt(Vector2, Camera, Boolean)`

- `SwipeDirection GetSwipe(Vector2, Vector2)`

- `Boolean FingerInTolerance(Finger)`

- `Boolean IsTouchOverNGui(Vector2, Boolean)`

- `Finger GetFinger(Int32)`

- `Boolean IsScreenPositionOverUI(Vector2)`

- `GameObject GetFirstUIElementFromCache()`

- `GameObject GetFirstUIElement(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class EasyTouch : MonoBehaviour
{
	private static TouchCancelHandler On_Cancel; // 0x0
	private static Cancel2FingersHandler On_Cancel2Fingers; // 0x8
	private static TouchStartHandler On_TouchStart; // 0x10
	private static TouchDownHandler On_TouchDown; // 0x18
	private static TouchUpHandler On_TouchUp; // 0x20
	private static SimpleTapHandler On_SimpleTap; // 0x28
	private static DoubleTapHandler On_DoubleTap; // 0x30
	private static LongTapStartHandler On_LongTapStart; // 0x38
	private static LongTapHandler On_LongTap; // 0x40
	private static LongTapEndHandler On_LongTapEnd; // 0x48
	private static DragStartHandler On_DragStart; // 0x50
	private static DragHandler On_Drag; // 0x58
	private static DragEndHandler On_DragEnd; // 0x60
	private static SwipeStartHandler On_SwipeStart; // 0x68
	private static SwipeHandler On_Swipe; // 0x70
	private static SwipeEndHandler On_SwipeEnd; // 0x78
	private static TouchStart2FingersHandler On_TouchStart2Fingers; // 0x80
	private static TouchDown2FingersHandler On_TouchDown2Fingers; // 0x88
	private static TouchUp2FingersHandler On_TouchUp2Fingers; // 0x90
	private static SimpleTap2FingersHandler On_SimpleTap2Fingers; // 0x98
	private static DoubleTap2FingersHandler On_DoubleTap2Fingers; // 0xa0
	private static LongTapStart2FingersHandler On_LongTapStart2Fingers; // 0xa8
	private static LongTap2FingersHandler On_LongTap2Fingers; // 0xb0
	private static LongTapEnd2FingersHandler On_LongTapEnd2Fingers; // 0xb8
	private static TwistHandler On_Twist; // 0xc0
	private static TwistEndHandler On_TwistEnd; // 0xc8
	private static PinchHandler On_Pinch; // 0xd0
	private static PinchInHandler On_PinchIn; // 0xd8
	private static PinchOutHandler On_PinchOut; // 0xe0
	private static PinchEndHandler On_PinchEnd; // 0xe8
	private static DragStart2FingersHandler On_DragStart2Fingers; // 0xf0
	private static Drag2FingersHandler On_Drag2Fingers; // 0xf8
	private static DragEnd2FingersHandler On_DragEnd2Fingers; // 0x100
	private static SwipeStart2FingersHandler On_SwipeStart2Fingers; // 0x108
	private static Swipe2FingersHandler On_Swipe2Fingers; // 0x110
	private static SwipeEnd2FingersHandler On_SwipeEnd2Fingers; // 0x118
	private static EasyTouchIsReadyHandler On_EasyTouchIsReady; // 0x120
	private static OverUIElementHandler On_OverUIElement; // 0x128
	private static UIElementTouchUpHandler On_UIElementTouchUp; // 0x130
	private static EasyTouch _instance; // 0x138
	private Gesture _currentGesture; // 0x18
	private List`1 _currentGestures; // 0x20
	public Boolean enable; // 0x28
	public Boolean enableRemote; // 0x29
	public GesturePriority gesturePriority; // 0x2c
	public Single StationaryTolerance; // 0x30
	public Single longTapTime; // 0x34
	public Single swipeTolerance; // 0x38
	public Single minPinchLength; // 0x3c
	public Single minTwistAngle; // 0x40
	public DoubleTapDetection doubleTapDetection; // 0x44
	public Single doubleTapTime; // 0x48
	public Boolean alwaysSendSwipe; // 0x4c
	public Boolean enable2FingersGesture; // 0x4d
	public Boolean enableTwist; // 0x4e
	public Boolean enablePinch; // 0x4f
	public Boolean enable2FingersSwipe; // 0x50
	public TwoFingerPickMethod twoFingerPickMethod; // 0x54
	public List`1 touchCameras; // 0x58
	public Boolean autoSelect; // 0x60
	public LayerMask pickableLayers3D; // 0x64
	public Boolean enable2D; // 0x68
	public LayerMask pickableLayers2D; // 0x6c
	public Boolean autoUpdatePickedObject; // 0x70
	public Boolean allowUIDetection; // 0x71
	public Boolean enableUIMode; // 0x72
	public Boolean autoUpdatePickedUI; // 0x73
	public Boolean enabledNGuiMode; // 0x74
	public LayerMask nGUILayers; // 0x78
	public List`1 nGUICameras; // 0x80
	public Boolean enableSimulation; // 0x88
	public KeyCode twistKey; // 0x8c
	public KeyCode swipeKey; // 0x90
	public Boolean showGuiInspector; // 0x94
	public Boolean showSelectInspector; // 0x95
	public Boolean showGestureInspector; // 0x96
	public Boolean showTwoFingerInspector; // 0x97
	public Boolean showSecondFingerInspector; // 0x98
	private EasyTouchInput input; // 0xa0
	private Finger[] fingers; // 0xa8
	public Texture secondFingerTexture; // 0xb0
	private TwoFingerGesture twoFinger; // 0xb8
	private Int32 oldTouchCount; // 0xc0
	private DoubleTap[] singleDoubleTap; // 0xc8
	private Finger[] tmpArray; // 0xd0
	private PickedObject pickedObject; // 0xd8
	private List`1 uiRaycastResultCache; // 0xe0
	private PointerEventData uiPointerEventData; // 0xe8
	private EventSystem uiEventSystem; // 0xf0

	public static EasyTouch instance { get; }
	public static Gesture current { get; }

	// RVA: 0x37564f4 VA: 0x7595d6e4f4
	public static Void add_On_Cancel(TouchCancelHandler value) { }
	// RVA: 0x375801c VA: 0x7595d7001c
	public static Void remove_On_Cancel(TouchCancelHandler value) { }
	// RVA: 0x375f394 VA: 0x7595d77394
	public static Void add_On_Cancel2Fingers(Cancel2FingersHandler value) { }
	// RVA: 0x375f450 VA: 0x7595d77450
	public static Void remove_On_Cancel2Fingers(Cancel2FingersHandler value) { }
	// RVA: 0x37565ac VA: 0x7595d6e5ac
	public static Void add_On_TouchStart(TouchStartHandler value) { }
	// RVA: 0x37580d4 VA: 0x7595d700d4
	public static Void remove_On_TouchStart(TouchStartHandler value) { }
	// RVA: 0x3756668 VA: 0x7595d6e668
	public static Void add_On_TouchDown(TouchDownHandler value) { }
	// RVA: 0x3758190 VA: 0x7595d70190
	public static Void remove_On_TouchDown(TouchDownHandler value) { }
	// RVA: 0x3756724 VA: 0x7595d6e724
	public static Void add_On_TouchUp(TouchUpHandler value) { }
	// RVA: 0x375824c VA: 0x7595d7024c
	public static Void remove_On_TouchUp(TouchUpHandler value) { }
	// RVA: 0x37567e0 VA: 0x7595d6e7e0
	public static Void add_On_SimpleTap(SimpleTapHandler value) { }
	// RVA: 0x3758308 VA: 0x7595d70308
	public static Void remove_On_SimpleTap(SimpleTapHandler value) { }
	// RVA: 0x3756ad0 VA: 0x7595d6ead0
	public static Void add_On_DoubleTap(DoubleTapHandler value) { }
	// RVA: 0x37585f8 VA: 0x7595d705f8
	public static Void remove_On_DoubleTap(DoubleTapHandler value) { }
	// RVA: 0x375689c VA: 0x7595d6e89c
	public static Void add_On_LongTapStart(LongTapStartHandler value) { }
	// RVA: 0x37583c4 VA: 0x7595d703c4
	public static Void remove_On_LongTapStart(LongTapStartHandler value) { }
	// RVA: 0x3756958 VA: 0x7595d6e958
	public static Void add_On_LongTap(LongTapHandler value) { }
	// RVA: 0x3758480 VA: 0x7595d70480
	public static Void remove_On_LongTap(LongTapHandler value) { }
	// RVA: 0x3756a14 VA: 0x7595d6ea14
	public static Void add_On_LongTapEnd(LongTapEndHandler value) { }
	// RVA: 0x375853c VA: 0x7595d7053c
	public static Void remove_On_LongTapEnd(LongTapEndHandler value) { }
	// RVA: 0x3756b8c VA: 0x7595d6eb8c
	public static Void add_On_DragStart(DragStartHandler value) { }
	// RVA: 0x37586b4 VA: 0x7595d706b4
	public static Void remove_On_DragStart(DragStartHandler value) { }
	// RVA: 0x3756c48 VA: 0x7595d6ec48
	public static Void add_On_Drag(DragHandler value) { }
	// RVA: 0x3758770 VA: 0x7595d70770
	public static Void remove_On_Drag(DragHandler value) { }
	// RVA: 0x3756d04 VA: 0x7595d6ed04
	public static Void add_On_DragEnd(DragEndHandler value) { }
	// RVA: 0x375882c VA: 0x7595d7082c
	public static Void remove_On_DragEnd(DragEndHandler value) { }
	// RVA: 0x3756dc0 VA: 0x7595d6edc0
	public static Void add_On_SwipeStart(SwipeStartHandler value) { }
	// RVA: 0x37588e8 VA: 0x7595d708e8
	public static Void remove_On_SwipeStart(SwipeStartHandler value) { }
	// RVA: 0x3756e7c VA: 0x7595d6ee7c
	public static Void add_On_Swipe(SwipeHandler value) { }
	// RVA: 0x37589a4 VA: 0x7595d709a4
	public static Void remove_On_Swipe(SwipeHandler value) { }
	// RVA: 0x3756f38 VA: 0x7595d6ef38
	public static Void add_On_SwipeEnd(SwipeEndHandler value) { }
	// RVA: 0x3758a60 VA: 0x7595d70a60
	public static Void remove_On_SwipeEnd(SwipeEndHandler value) { }
	// RVA: 0x3756ff4 VA: 0x7595d6eff4
	public static Void add_On_TouchStart2Fingers(TouchStart2FingersHandler value) { }
	// RVA: 0x3758b1c VA: 0x7595d70b1c
	public static Void remove_On_TouchStart2Fingers(TouchStart2FingersHandler value) { }
	// RVA: 0x37570b0 VA: 0x7595d6f0b0
	public static Void add_On_TouchDown2Fingers(TouchDown2FingersHandler value) { }
	// RVA: 0x3758bd8 VA: 0x7595d70bd8
	public static Void remove_On_TouchDown2Fingers(TouchDown2FingersHandler value) { }
	// RVA: 0x375716c VA: 0x7595d6f16c
	public static Void add_On_TouchUp2Fingers(TouchUp2FingersHandler value) { }
	// RVA: 0x3758c94 VA: 0x7595d70c94
	public static Void remove_On_TouchUp2Fingers(TouchUp2FingersHandler value) { }
	// RVA: 0x3757228 VA: 0x7595d6f228
	public static Void add_On_SimpleTap2Fingers(SimpleTap2FingersHandler value) { }
	// RVA: 0x3758d50 VA: 0x7595d70d50
	public static Void remove_On_SimpleTap2Fingers(SimpleTap2FingersHandler value) { }
	// RVA: 0x3757518 VA: 0x7595d6f518
	public static Void add_On_DoubleTap2Fingers(DoubleTap2FingersHandler value) { }
	// RVA: 0x3759040 VA: 0x7595d71040
	public static Void remove_On_DoubleTap2Fingers(DoubleTap2FingersHandler value) { }
	// RVA: 0x37572e4 VA: 0x7595d6f2e4
	public static Void add_On_LongTapStart2Fingers(LongTapStart2FingersHandler value) { }
	// RVA: 0x3758e0c VA: 0x7595d70e0c
	public static Void remove_On_LongTapStart2Fingers(LongTapStart2FingersHandler value) { }
	// RVA: 0x37573a0 VA: 0x7595d6f3a0
	public static Void add_On_LongTap2Fingers(LongTap2FingersHandler value) { }
	// RVA: 0x3758ec8 VA: 0x7595d70ec8
	public static Void remove_On_LongTap2Fingers(LongTap2FingersHandler value) { }
	// RVA: 0x375745c VA: 0x7595d6f45c
	public static Void add_On_LongTapEnd2Fingers(LongTapEnd2FingersHandler value) { }
	// RVA: 0x3758f84 VA: 0x7595d70f84
	public static Void remove_On_LongTapEnd2Fingers(LongTapEnd2FingersHandler value) { }
	// RVA: 0x3757d2c VA: 0x7595d6fd2c
	public static Void add_On_Twist(TwistHandler value) { }
	// RVA: 0x3759854 VA: 0x7595d71854
	public static Void remove_On_Twist(TwistHandler value) { }
	// RVA: 0x3757de8 VA: 0x7595d6fde8
	public static Void add_On_TwistEnd(TwistEndHandler value) { }
	// RVA: 0x3759910 VA: 0x7595d71910
	public static Void remove_On_TwistEnd(TwistEndHandler value) { }
	// RVA: 0x3757a3c VA: 0x7595d6fa3c
	public static Void add_On_Pinch(PinchHandler value) { }
	// RVA: 0x3759564 VA: 0x7595d71564
	public static Void remove_On_Pinch(PinchHandler value) { }
	// RVA: 0x3757af8 VA: 0x7595d6faf8
	public static Void add_On_PinchIn(PinchInHandler value) { }
	// RVA: 0x3759620 VA: 0x7595d71620
	public static Void remove_On_PinchIn(PinchInHandler value) { }
	// RVA: 0x3757bb4 VA: 0x7595d6fbb4
	public static Void add_On_PinchOut(PinchOutHandler value) { }
	// RVA: 0x37596dc VA: 0x7595d716dc
	public static Void remove_On_PinchOut(PinchOutHandler value) { }
	// RVA: 0x3757c70 VA: 0x7595d6fc70
	public static Void add_On_PinchEnd(PinchEndHandler value) { }
	// RVA: 0x3759798 VA: 0x7595d71798
	public static Void remove_On_PinchEnd(PinchEndHandler value) { }
	// RVA: 0x3757808 VA: 0x7595d6f808
	public static Void add_On_DragStart2Fingers(DragStart2FingersHandler value) { }
	// RVA: 0x3759330 VA: 0x7595d71330
	public static Void remove_On_DragStart2Fingers(DragStart2FingersHandler value) { }
	// RVA: 0x37578c4 VA: 0x7595d6f8c4
	public static Void add_On_Drag2Fingers(Drag2FingersHandler value) { }
	// RVA: 0x37593ec VA: 0x7595d713ec
	public static Void remove_On_Drag2Fingers(Drag2FingersHandler value) { }
	// RVA: 0x3757980 VA: 0x7595d6f980
	public static Void add_On_DragEnd2Fingers(DragEnd2FingersHandler value) { }
	// RVA: 0x37594a8 VA: 0x7595d714a8
	public static Void remove_On_DragEnd2Fingers(DragEnd2FingersHandler value) { }
	// RVA: 0x37575d4 VA: 0x7595d6f5d4
	public static Void add_On_SwipeStart2Fingers(SwipeStart2FingersHandler value) { }
	// RVA: 0x37590fc VA: 0x7595d710fc
	public static Void remove_On_SwipeStart2Fingers(SwipeStart2FingersHandler value) { }
	// RVA: 0x3757690 VA: 0x7595d6f690
	public static Void add_On_Swipe2Fingers(Swipe2FingersHandler value) { }
	// RVA: 0x37591b8 VA: 0x7595d711b8
	public static Void remove_On_Swipe2Fingers(Swipe2FingersHandler value) { }
	// RVA: 0x375774c VA: 0x7595d6f74c
	public static Void add_On_SwipeEnd2Fingers(SwipeEnd2FingersHandler value) { }
	// RVA: 0x3759274 VA: 0x7595d71274
	public static Void remove_On_SwipeEnd2Fingers(SwipeEnd2FingersHandler value) { }
	// RVA: 0x375f50c VA: 0x7595d7750c
	public static Void add_On_EasyTouchIsReady(EasyTouchIsReadyHandler value) { }
	// RVA: 0x375f5c8 VA: 0x7595d775c8
	public static Void remove_On_EasyTouchIsReady(EasyTouchIsReadyHandler value) { }
	// RVA: 0x3757ea4 VA: 0x7595d6fea4
	public static Void add_On_OverUIElement(OverUIElementHandler value) { }
	// RVA: 0x375f684 VA: 0x7595d77684
	public static Void remove_On_OverUIElement(OverUIElementHandler value) { }
	// RVA: 0x3757f60 VA: 0x7595d6ff60
	public static Void add_On_UIElementTouchUp(UIElementTouchUpHandler value) { }
	// RVA: 0x375f740 VA: 0x7595d77740
	public static Void remove_On_UIElementTouchUp(UIElementTouchUpHandler value) { }
	// RVA: 0x375aee8 VA: 0x7595d72ee8
	public static EasyTouch get_instance() { }
	// RVA: 0x375d044 VA: 0x7595d75044
	public static Gesture get_current() { }
	// RVA: 0x375f7fc VA: 0x7595d777fc
	public Void .ctor() { }
	// RVA: 0x375fb68 VA: 0x7595d77b68
	private Void OnEnable() { }
	// RVA: 0x375fb90 VA: 0x7595d77b90
	private Void Awake() { }
	// RVA: 0x375fb94 VA: 0x7595d77b94
	private Void Start() { }
	// RVA: 0x375fb8c VA: 0x7595d77b8c
	private Void Init() { }
	// RVA: 0x375fef4 VA: 0x7595d77ef4
	private Void OnDrawGizmos() { }
	// RVA: 0x375fef8 VA: 0x7595d77ef8
	private Void Update() { }
	// RVA: 0x376262c VA: 0x7595d7a62c
	private Void LateUpdate() { }
	// RVA: 0x37603fc VA: 0x7595d783fc
	private Void UpdateTouches(Boolean realTouch, Int32 touchCount) { }
	// RVA: 0x3762734 VA: 0x7595d7a734
	private Void ResetTouches() { }
	// RVA: 0x3761b78 VA: 0x7595d79b78
	private Void OneFinger(Int32 fingerIndex) { }
	// RVA: 0x37630d0 VA: 0x7595d7b0d0
	private IEnumerator SingleOrDouble(Int32 fingerIndex) { }
	// RVA: 0x3762bcc VA: 0x7595d7abcc
	private Void CreateGesture(Int32 touchIndex, EvtType message, Finger finger, SwipeDirection swipe, Single swipeLength, Vector2 swipeVector) { }
	// RVA: 0x37609c4 VA: 0x7595d789c4
	private Void TwoFinger() { }
	// RVA: 0x3764320 VA: 0x7595d7c320
	private Void DetectPinch(Single currentDelta) { }
	// RVA: 0x3764630 VA: 0x7595d7c630
	private Void DetecTwist(Vector2 previousDistance, Vector2 currentDistance, Single currentDelta) { }
	// RVA: 0x3763de0 VA: 0x7595d7bde0
	private Void CreateStateEnd2Fingers(GestureType gesture, Vector2 startPosition, Vector2 position, Vector2 deltaPosition, Single time, Boolean realEnd, Single fingerDistance, Single twist, Single pinch) { }
	// RVA: 0x37648c8 VA: 0x7595d7c8c8
	private IEnumerator SingleOrDouble2Fingers() { }
	// RVA: 0x37600d8 VA: 0x7595d780d8
	private Void CreateGesture2Finger(EvtType message, Vector2 startPosition, Vector2 position, Vector2 deltaPosition, Single actionTime, SwipeDirection swipe, Single swipeLength, Vector2 swipeVector, Single twist, Single pinch, Single twoDistance) { }
	// RVA: 0x3763a78 VA: 0x7595d7ba78
	private Int32 GetTwoFinger(Int32 index) { }
	// RVA: 0x3763aec VA: 0x7595d7baec
	private Boolean GetTwoFingerPickedObject() { }
	// RVA: 0x3763c04 VA: 0x7595d7bc04
	private Boolean GetTwoFingerPickedUIElement() { }
	// RVA: 0x37632d8 VA: 0x7595d7b2d8
	private Void RaiseEvent(EvtType evnt, Gesture gesture) { }
	// RVA: 0x3762790 VA: 0x7595d7a790
	private Boolean GetPickedGameObject(Finger finger, Boolean isTowFinger) { }
	// RVA: 0x376493c VA: 0x7595d7c93c
	private Boolean GetGameObjectAt(Vector2 position, Camera cam, Boolean isGuiCam) { }
	// RVA: 0x3762e00 VA: 0x7595d7ae00
	private SwipeDirection GetSwipe(Vector2 start, Vector2 end) { }
	// RVA: 0x3762dcc VA: 0x7595d7adcc
	private Boolean FingerInTolerance(Finger finger) { }
	// RVA: 0x3763154 VA: 0x7595d7b154
	private Boolean IsTouchOverNGui(Vector2 position, Boolean isTwoFingers) { }
	// RVA: 0x3764b64 VA: 0x7595d7cb64
	private Finger GetFinger(Int32 finderId) { }
	// RVA: 0x37629f4 VA: 0x7595d7a9f4
	private Boolean IsScreenPositionOverUI(Vector2 position) { }
	// RVA: 0x3762b44 VA: 0x7595d7ab44
	private GameObject GetFirstUIElementFromCache() { }
	// RVA: 0x3764bc4 VA: 0x7595d7cbc4
	private GameObject GetFirstUIElement(Vector2 position) { }
	// RVA: 0x3764bec VA: 0x7595d7cbec
	public static Boolean IsFingerOverUIElement(Int32 fingerIndex) { }
	// RVA: 0x3764c94 VA: 0x7595d7cc94
	public static GameObject GetCurrentPickedUIElement(Int32 fingerIndex, Boolean isTwoFinger) { }
	// RVA: 0x3764dc8 VA: 0x7595d7cdc8
	public static GameObject GetCurrentPickedObject(Int32 fingerIndex, Boolean isTwoFinger) { }
	// RVA: 0x375d250 VA: 0x7595d75250
	public static GameObject GetGameObjectAt(Vector2 position, Boolean isTwoFinger) { }
	// RVA: 0x3764ea0 VA: 0x7595d7cea0
	public static Int32 GetTouchCount() { }
	// RVA: 0x3764f30 VA: 0x7595d7cf30
	public static Void ResetTouch(Int32 fingerIndex) { }
	// RVA: 0x3764fbc VA: 0x7595d7cfbc
	public static Void SetEnabled(Boolean enable) { }
	// RVA: 0x3764ff4 VA: 0x7595d7cff4
	public static Boolean GetEnabled() { }
	// RVA: 0x376507c VA: 0x7595d7d07c
	public static Void SetEnableUIDetection(Boolean enable) { }
	// RVA: 0x3765100 VA: 0x7595d7d100
	public static Boolean GetEnableUIDetection() { }
	// RVA: 0x375b100 VA: 0x7595d73100
	public static Void SetUICompatibily(Boolean value) { }
	// RVA: 0x3765188 VA: 0x7595d7d188
	public static Boolean GetUIComptability() { }
	// RVA: 0x3765214 VA: 0x7595d7d214
	public static Void SetAutoUpdateUI(Boolean value) { }
	// RVA: 0x3765294 VA: 0x7595d7d294
	public static Boolean GetAutoUpdateUI() { }
	// RVA: 0x376531c VA: 0x7595d7d31c
	public static Void SetNGUICompatibility(Boolean value) { }
	// RVA: 0x376539c VA: 0x7595d7d39c
	public static Boolean GetNGUICompatibility() { }
	// RVA: 0x37549ac VA: 0x7595d6c9ac
	public static Void SetEnableAutoSelect(Boolean value) { }
	// RVA: 0x3765424 VA: 0x7595d7d424
	public static Boolean GetEnableAutoSelect() { }
	// RVA: 0x37654ac VA: 0x7595d7d4ac
	public static Void SetAutoUpdatePickedObject(Boolean value) { }
	// RVA: 0x376552c VA: 0x7595d7d52c
	public static Boolean GetAutoUpdatePickedObject() { }
	// RVA: 0x375ac4c VA: 0x7595d72c4c
	public static Void Set3DPickableLayer(LayerMask mask) { }
	// RVA: 0x375ab28 VA: 0x7595d72b28
	public static LayerMask Get3DPickableLayer() { }
	// RVA: 0x37655b4 VA: 0x7595d7d5b4
	public static Void AddCamera(Camera cam, Boolean guiCam) { }
	// RVA: 0x37656fc VA: 0x7595d7d6fc
	public static Void RemoveCamera(Camera cam) { }
	// RVA: 0x3765898 VA: 0x7595d7d898
	public static Camera GetCamera(Int32 index) { }
	// RVA: 0x375acc8 VA: 0x7595d72cc8
	public static Void SetEnable2DCollider(Boolean value) { }
	// RVA: 0x3765978 VA: 0x7595d7d978
	public static Boolean GetEnable2DCollider() { }
	// RVA: 0x375ae6c VA: 0x7595d72e6c
	public static Void Set2DPickableLayer(LayerMask mask) { }
	// RVA: 0x375ad48 VA: 0x7595d72d48
	public static LayerMask Get2DPickableLayer() { }
	// RVA: 0x3765a00 VA: 0x7595d7da00
	public static Void SetGesturePriority(GesturePriority value) { }
	// RVA: 0x3765a7c VA: 0x7595d7da7c
	public static GesturePriority GetGesturePriority() { }
	// RVA: 0x3765afc VA: 0x7595d7dafc
	public static Void SetStationaryTolerance(Single tolerance) { }
	// RVA: 0x3765b80 VA: 0x7595d7db80
	public static Single GetStationaryTolerance() { }
	// RVA: 0x3765c00 VA: 0x7595d7dc00
	public static Void SetLongTapTime(Single time) { }
	// RVA: 0x3765c84 VA: 0x7595d7dc84
	public static Single GetlongTapTime() { }
	// RVA: 0x3765d04 VA: 0x7595d7dd04
	public static Void SetDoubleTapTime(Single time) { }
	// RVA: 0x3765d88 VA: 0x7595d7dd88
	public static Single GetDoubleTapTime() { }
	// RVA: 0x3765e08 VA: 0x7595d7de08
	public static Void SetDoubleTapMethod(DoubleTapDetection detection) { }
	// RVA: 0x3765e84 VA: 0x7595d7de84
	public static DoubleTapDetection GetDoubleTapMethod() { }
	// RVA: 0x3765f04 VA: 0x7595d7df04
	public static Void SetSwipeTolerance(Single tolerance) { }
	// RVA: 0x3765f88 VA: 0x7595d7df88
	public static Single GetSwipeTolerance() { }
	// RVA: 0x3766008 VA: 0x7595d7e008
	public static Void SetEnable2FingersGesture(Boolean enable) { }
	// RVA: 0x3766088 VA: 0x7595d7e088
	public static Boolean GetEnable2FingersGesture() { }
	// RVA: 0x3766110 VA: 0x7595d7e110
	public static Void SetTwoFingerPickMethod(TwoFingerPickMethod pickMethod) { }
	// RVA: 0x376618c VA: 0x7595d7e18c
	public static TwoFingerPickMethod GetTwoFingerPickMethod() { }
	// RVA: 0x376620c VA: 0x7595d7e20c
	public static Void SetEnablePinch(Boolean enable) { }
	// RVA: 0x376628c VA: 0x7595d7e28c
	public static Boolean GetEnablePinch() { }
	// RVA: 0x3766314 VA: 0x7595d7e314
	public static Void SetMinPinchLength(Single length) { }
	// RVA: 0x3766398 VA: 0x7595d7e398
	public static Single GetMinPinchLength() { }
	// RVA: 0x3766418 VA: 0x7595d7e418
	public static Void SetEnableTwist(Boolean enable) { }
	// RVA: 0x3766498 VA: 0x7595d7e498
	public static Boolean GetEnableTwist() { }
	// RVA: 0x3766520 VA: 0x7595d7e520
	public static Void SetMinTwistAngle(Single angle) { }
	// RVA: 0x37665a4 VA: 0x7595d7e5a4
	public static Single GetMinTwistAngle() { }
	// RVA: 0x3766624 VA: 0x7595d7e624
	public static Boolean GetSecondeFingerSimulation() { }
	// RVA: 0x37666b0 VA: 0x7595d7e6b0
	public static Void SetSecondFingerSimulation(Boolean value) { }
}
```