package tech;

/**
 * @author padraigmervyn
 *
 */
public class Company extends Square {
	private String companyName;
	private String area;
	private int squareNumber;
	private int squarePrice;
	private int officePrice;
	private int buildingPrice;
	
	/**
	 * Default constructor
	 */
	public Company() {
		
	}
	/**
	 * Constructor with args
	 */
	public Company(String companyName, String area, int squareNumber, int squarePrice, int officePrice, int buildingPrice) {
		this.companyName = companyName;
		this.area = area;
		this.squareNumber = squareNumber;
		this.squarePrice = squarePrice;
		this.officePrice = officePrice;
		this.buildingPrice = buildingPrice;
		
	}
	
	/**
	 * @return the companyName
	 */
	public String getCompanyName() {
		return companyName;
	}
	/**
	 * @param companyName the companyName to set
	 */
	public void setCompanyName(String companyName) {
		this.companyName = companyName;
	}
	/**
	 * @return the area
	 */
	public String getArea() {
		return area;
	}
	/**
	 * @param area the area to set
	 */
	public void setArea(String area) {
		this.area = area;
	}
	/**
	 * @return the squareNumber
	 */
	public int getSquareNumber() {
		return squareNumber;
	}
	/**
	 * @param squareNumber the squareNumber to set
	 */
	public void setSquareNumber(int squareNumber) {
		this.squareNumber = squareNumber;
	}
	/**
	 * @return the squarePrice
	 */
	public int getSquarePrice() {
		return squarePrice;
	}
	/**
	 * @param squarePrice the squarePrice to set
	 */
	public void setSquarePrice(int squarePrice) {
		this.squarePrice = squarePrice;
	}
	/**
	 * @return the officePrice
	 */
	public int getOfficePrice() {
		return officePrice;
	}
	/**
	 * @param officePrice the officePrice to set
	 */
	public void setOfficePrice(int officePrice) {
		this.officePrice = officePrice;
	}
	/**
	 * @return the buildingPrice
	 */
	public int getBuildingPrice() {
		return buildingPrice;
	}
	/**
	 * @param buildingPrice the buildingPrice to set
	 */
	public void setBuildingPrice(int buildingPrice) {
		this.buildingPrice = buildingPrice;
	}
	
	/**
	 * ADD THE NAME OF THE PLAYER
	 */
	@Override
	public void displayAll() {
		
		System.out.println("You have landed on: "+this.area+" a partner of "+this.companyName);
		System.out.println("Square details: ");
		System.out.println("This square costs: "+this.squarePrice);
		System.out.println("To develop an Office on this square you will have to pay: "+this.officePrice);
		System.out.println("To develop a Building on this square you will have to pay: "+this.buildingPrice);
		
		
	}
	
}

