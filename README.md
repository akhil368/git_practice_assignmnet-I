
let bag="";
    // console.log(str.length);
    for(let i=0;i<str.length-1;i++)
    {
        bag=str[i]+bag;
    }
    
    if(bag==str)
    {
        console.log("Yes");
    }
    else
    {
        console.log("No");
    }