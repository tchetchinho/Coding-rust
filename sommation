
fn main(){
    println!("Ceci est un programme qui calcule la somme de 0 à N \n");

    let mut n = String::new();

    println!("Entrez un nombre : ");
    std::io::stdin().read_line(&mut n).expect("Failed to read line");
    let n: u16 = n.trim().parse().expect("Not a number");
    let mut som = n;

    for i in 0..n as u16{
        som += i;
        print!("{} + ", i);
    }println!("{} = {}", n, som);

}
