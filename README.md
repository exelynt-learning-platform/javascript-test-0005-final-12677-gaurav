let totalRows = 5;
let currentNum = 1;

for (let i = 1; i <= totalRows; i++) {

  let row = "";

  for (let j = 1; j <= i; j++) {
    row += currentNum + " ";
    currentNum++;
  }

  console.log(row.trim());
}
