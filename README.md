# Simple Spam Filter
Regular Expressions by Building a Spam Filter

## Description
In this spam filter project, We learned about capture groups, positive lookaheads, negative lookaheads, and other techniques to match any text you want.

### Regexs
`const helpRegex = /please help|assist me/i;` <br/>
`const dollarRegex = /[0-9]+ (?:hundred|thousand|million|billion)? dollars/i;`<br/>
`const freeRegex = /(?:^|\s)fr[e3][e3] m[o0]n[e3]y(?:$|\s)/i;`<br/>
`const stockRegex = /(?:^|\s)[s5][t7][o0][c{[(]k [a@4]l[e3]r[t7](?:$|\s)/i;`<br/>
`const dearRegex = /(?:^|\s)d[e3][a@4]r fr[i1|][e3]nd(?:$|\s)/i;`<br/>
