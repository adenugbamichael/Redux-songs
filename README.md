# songs

<td align="center">
<br/>
<div>
<a href="https://github.com/adenugbamichael/songs-redux">
<img height="216" width="345" alt="songs-redux demo" src="/src/assets/songs.gif"/>
</a>
</div>
<br />
</td>

#### The mapStateToProps function was updated to communicate the favoriteTitle piece of state into the component

#### Because the mapStateToProps function is now returning an object with a favoriteTitle property, the React component now has access to a prop of this.props.favoriteTitle

#### The mapping function inside of renderList compares the title of the current song it is iterating over to this.props.favoriteTitle
