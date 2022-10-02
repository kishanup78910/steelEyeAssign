# steelEye Assignemnt Kishan
I am unable to optimise the code but is have done first ans second question 



1. Explain what the simple List component does.
ans  -- - -Listitems. WrappedListComponent creates an unordered list. It takes an array (items) of strings(text) as props. For each item in the array, it maps through all and displays their content on the screen with a background color of 'Red'. If one item is selected, then it displays it with a different background color (Green). The user can click on an item and it will get selected and will get background color of Green.




2-. What problems/warnings are there with the code?

ans - - -a--Syntax Error in useState() : const [setSelectedIndex, selectedIndex] = useState(); setSelectedIndex should be 2nd params because value store in setSelected will update our state. const[selectedIndex,setSelectedIndex]=useState(); this is the correct syntax.

    b--Type Error in shape() function shapeOf() is not any function
WrappedListComponent.propTypes = { items: PropTypes.arrayOf( PropTypes.shape({ text: PropTypes.string.isRequired, }) ), };
